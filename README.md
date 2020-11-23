title: battd

# NAME
battd - battery monitor written in POSIX sh

# SYNOPSIS
***battd*** [_-c config-file_]


# DESCRIPTION
Sends notification with when battery reached a certain level.  

# OPTIONS
***-c*** config-file
Read config from _config-file_ instead of _$XDG\_CONFIG\_HOME_ 
or ~/.config if _$XDG\_CONFIG\_HOME_ is not defined.

## -h	
print options and exit.

# SEE ALSO
	batsignal(1)
