# shell-clock
View current : Time, Date, Day of the Week, Day of the Year

For Convenience:

  Add this to the end of your .bashrc file:
  
    alias tdi="/your/path/to/the/timedate-viewer"
  
 Now you can type "tdi" for Time / Date information.
 

# One-Line/Single-Command

Single Command ; Colored ; US and EU Versions ; 2 Output Lines

EURO TIME-DATE-FORMAT:

    echo -e "\e[37m$(date +"%H:%M    %d.%m: %Y    %n$(echo -e "\e[36m%A\e[0m")  $(echo -e "\e[36m Day:  %j\e[0m")")\e[0m"

US TIME-DATE-FORMAT:

    echo -e "\e[37m$(date +"%I:%M    %m.%d: %Y    %n$(echo -e "\e[36m%A\e[0m")  $(echo -e "\e[36m Day:  %j\e[0m")")\e[0m"
