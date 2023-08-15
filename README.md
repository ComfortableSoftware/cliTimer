

# clitimer

  - A simple and semi accurate timer utility to time commandline executions times.
    - #### My preferred installation method.
      1. clone the repository.
      2. 'cd \<directory cloned to\>'
      3. 'sudo pip install .'
  - ### COMMAND LINE OPTIONS
    - 'clitimer -h' for help.
    - 'clitimer -t' returns a date in the format '2022/06/06 19:25:04.354975'
    - 'clitimer -m' returns a date in the format '1654565154.486381'
    - 'clitimer -r \<start time\> \<end time\>' returns the result of \<end time\> - \<start time\> in the format '2022/06/06 19:25:04.354975'
      - Start time and end time can be entered in either supported format.
      - The '-t' format needs to be quoted, the '-m' can be either quoted or not.
    - 'clitimer -s \<start time\> \<end time\>' returns the result of \<end time\> - \<start time\> in the format '1654565154.486381'
      - Start time and end time can be entered in either supported format.
      - The '-t' format needs to be quoted, the '-m' can be either quoted or not.
    - '-f' switch to full result format.
      - Full result format will be one of the following based on the '-r' or '-s' choice made.
      - ---
        - End Time 1654565154.486381
      - Start Time 2022/06/06 19:25:04.354975
    - =     Result 0000/00/00/ 00:00:51.868594
      - ___
      - or
      - ___
        - End Time 1654565154.486381
      - Start Time 2022/06/06 19:25:04.354975
    - =     Result 51.868594
    - Start and end times are always displayed as entered.
  - ##### KNOWN ISSUES
    - Using '-t' format is less accurate than using -m format.
      - Easiest workaround is to enter start and end times as '-m' and get results as '-r'.
