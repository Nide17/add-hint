## add-hint - Code for Assignment 2 for ILSE, 04-801 B2, Fall 2022
    
__USAGE__

add-hint - Performs batch hint adding to the files or directories


__SYNOPSIS__

__add-hint [options] < pattern > < hint > [directories]__
    


__DESCRIPTION__
    
Performs a batch hint adding to the files or directories by adding a hint to the end of their names, based on a glob wildcard (GLOBBING). If one or more directories are specified, batch hint adding will operate to files inside those directories; otherwise it will operate on all files matching the wildcard in the cwd.


__< pattern >__ is an glob wildcard as used by find, <hint> is any specified hint.
    



__Options can be one or more of:__
    

&nbsp; -d | --dirs-only          Limit the hint adding to directories only.
    
&nbsp; -f | --files-only         Limit the hint adding to regular files only.
    
&nbsp; -h | --help               Print this usage message and exit
    
&nbsp; -i | --interactive        Do not automatically add hints; instead, provide a list of original and, 
                                 modified names and ask the user to confirm the hint adding before it happens.
    
&nbsp; -r | --recursive          Recursively descend directories; otherwise,
                                 processes only files in the directories specified, or cwd.
    


__IMPORTANCE__

Someone may need to use add-hint, when there is a need of adding a particular hint to the end of one or multiple files or directories at once to make them more rememberable, helping to avoid the naming confusion, directing others who may want to use the files or directories in the future and making it easier for searching them.



__GETTING STARTED__

- Clone this repository to get the add-hint script and its test_add_hint.
- Make both scripts executable as: chmod +x add_hint and chmod +x test_add_hint
- Run the add_hint from its containing directory on the command line, with the options, pattern, hint, and directories as shown above(__SYNOPSIS__)
- Check if it has effects.



__TESTING__

This script can be tested using the test_add_hint script which is also on this repository. The test_add_hint script to first create a shell variable that points to the directory containing the add-hint script and called it wd as: export wd="/path/dir/to/add-hint". Then, run the test_add_hint script on the command line from its containing directory and you should be able to see the real-time test results.
    


 __KEYWORDS__

   ILSE          CMU              Assignment2               add-hint               Linux           Shell scripts



  __AUTHOR__
    
 Written by parmenin (Niyomwungeri Parmenide ISHIMWE) at CMU-Africa - MSIT 
    

    
 __DATE__
    
 November 14, 2022" 
