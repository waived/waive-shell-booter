////////////////////////////////////////////////////
// W a i v e   S h e l l   B o o t e r   v 1 . 1  //
////////////////////////////////////////////////////

Overview: A shell booter is a tool that allows its user to launch DDoS (Distributed Denial-of-Service) attacks
          against an endpoint on the internet by leveraging backdoored websites. Said websites have a specific
          type of backdoor installed on them known as a "DoS shell" which is commonly written in PHP, but can
          also come in the form of ASP or JS.

          This specific shell booter is made compatible with Waive DoS Shell (github.com/waived/waive-shell)

Features:
          This version of Waive Shell Booter is NOT multi-threaded, so depending on the latency/availability
          of the shell(s) loaded into this program will determine the turnover time of each attack. Future
          versions will be multi-threaded.

          Shell(s) will be put into a .txt list and loaded directly into this programmed instead of having
          each shell hard-coded. The format for each shell should be:

                 http://www.SOMESITE.com/whatever/waiveshell.php

          Note: as long as the URL ends in .php, Waive Shell Booter will attempt to pass attack parameters
          to the backdoor. Do no included any sort of query or leading forward-slash.

          Waive Shell Booter also a shell-check function which will send out HTTP-HEAD requests in attempt
          to retrieve a "200 OK" response. If said response is not received, the shell will be considered
          dead.

          Additionally, Waive Shell Booter has an option to build a waiveshell.pph copy for the user. This
          way save some time when pulling it from its github repository, or God forbid this account gets removed.

Known bugs:
          None, but please leave a comment if one is found. Thank you.


Please use responsibly.







