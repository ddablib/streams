# Change Log for Stream Extension Classes

## v3.1.2 of 12 January 2014

+ Fixed problems with compiler directives in project, demo and some test source files that were causing compilation to fail on Delphi XE5.
+ Made change to test units and to VCL demo programs to enable method inlining to work correctly with Delphi XE3 and later.
+ Fixed bug in _IStreamWrapDemoFMX_ demo program where program failed to compile on Delphi XE4 because several of the form's controls could not be found.
+ Minor documentation tweaks and corrections.
+ Licensed change log under Mozilla Public License v2.0.

## v3.1.1 of 28 January 2013

+ Unit names references in project source files are now qualified with namespace name on Delphi XE2 and later.
+ Changes to demo projects:
  + Default form font changed to Arial.
  + Forms are no longer scaled.
  + Fixed error in _IStreamWrap_ demo where Unicode text was not been read correctly from memory streams.
  + Project group files removed.
  + New FireMonkey 2 demo project that demonstrates _PJIStreams_ unit.
+ Project source license changed to Mozilla Public License v2.0. (Demos and test project now placed in public domain).
+ MPL text file and documentation wiki short-cut have had names changed.
+ Updated documentation.

## v3.1 of 08 October 2011

+ Added overloads for 64 bit integer parameters to _TStream_ descendant _SetSize_ and _Seek_ methods.
+ Implemented proper support to _IStream_ implementations for large (64 bit) integer data sizes, seeks and copies.
+ Changed visibility of all _IStream_ implementation methods from protected to public.
+ Implemented work around for error in seeking from end of wrapped _TStringStream_ objects. This is caused by a bug in non-Unicode _TStringStream_'s implementation of _Seek_.
+ Reinstated DUnit tests. They were revised, extended and corrected and made compatible with Unicode Delphis.
+ Demo projects now explicitly import project units so that they will work when the required units are not installed.
+ New project and project group files for later versions of Delphi added to demo and unit test projects.
+ Documented units using XMLDoc comments.
+ Updated documentation.

## v3.0 of 07 October 2009

+ Removed deprecated _PJResWriterStreams_ unit from project.
+ Removed demo programs for classes in _PJResWriterStreams_ unit.
+ Switched off "unsafe" compiler warnings.
+ Updated demo code to compile with Delphi 2010.
+ Deleted user guide from project: superseded by project's online Wiki.
+ Removed DUnit tests.
+ Changed to Mozilla Public License v1.1.
+ Updated documentation.

## v2.0.1 of 23 November 2003

+ Made changes in _PJIStreams_ unit:
  + Fixed some minor bugs.
  + Added simplified method for getting stream name.
  + Modified use of task allocator.

## v2.0 of 30 September 2001

+ Added new unit providing classes that implement the _IStream_ interface.
+ Renamed earlier units and classes in keeping with my library naming conventions.
+ Added some demo programs to the release.

## v1.0 of 02 July 2000

+ Original version - stream wrapper base class and resource file encapsulation classes only.
