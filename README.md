# SYSTEM HEALTH STATUS

## ABSTRACT

* The project aims for checking the Linux system health with a shell script.

* This is a short, lightweight script that gets the necessary information and status like
hostname, kernel version, CPU, Uptime, memory/ disk usage using native Linux utilities
and doesn't take up much room.

* The Script uses hostname, uname, arch, uptime, cat, mpstat, ps, df, free, head commands
to get system information and cut, grep, awk and sed for text processing.

* The output of the script is a text file that will be generated in the current directory.

* A variable is set to provide an email address to which the script can send the report file.

* Apart from system status, the script will check a predefined threshold for CPU load and
filesystem size.

## RUN USING
* `chmod +x system_health_status.sh`
* `./system_health_status.sh`

## RESULTS

  
