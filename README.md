# add-hint - Code for Assignment 2 for ILSE, 04-801 B2, Fall 2022
    
__USAGE__: add-hint - Performs batch hint adding to the files or directories

 __SYNOPSIS__
 
 __add-hint [options] <pattern> <hint> [directories]__
    
 __DESCRIPTION__
    
Performs a batch hint adding to the files or directories by adding a hint to the end of their names, based on a glob wildcard (GLOBBING). If one or more directories are specified, batch hint adding will operate to files inside those directories; otherwise it will operate on all files matching the wildcard in the cwd.
    
 __<pattern>__ is an glob wildcard as used by find, <hint> is any specified hint.
    
__Options can be one or more of:__
    
&nbsp; -d | --dirs-only          Limit the hint adding to directories only.
    
&nbsp; -f | --files-only         Limit the hint adding to regular files only.
    
&nbsp; -h | --help               Print this usage message and exit
    
&nbsp; -i | --interactive        Do not automatically add hints; instead, provide a list of original and, 
                                 modified names and ask the user to confirm the hint adding before it happens.
    
&nbsp; -r | --recursive          Recursively descend directories; otherwise,
                                 processes only files in the directories specified, or cwd.
    
 __AUTHOR__
    
 Written by parmenin (Niyomwungeri Parmenide ISHIMWE) at CMU-Africa - MSIT 
    
 __DATE__
    
 November 14, 2022" 
