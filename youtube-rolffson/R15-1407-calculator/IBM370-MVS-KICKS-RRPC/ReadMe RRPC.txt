
files for YouTube video on rolffson's channel,
as shown in "IBM 1401 programming: the 1407 inquiry terminal - R15"
https://youtu.be/GZtLMMuLUuY

(C) rolffson 2021
free for educational use

RRPC (rolffson's ridiculous pocket calculator)
tested on hercules/tk4 with KICKS

source files:
RRPCALC.txt - COBOL source
RRPCMSD.txt - KICKS map file
transaction code definition:
dataset on host can normally be found in 'HERC01.KICKSSYS.V1R5M0.INSTLIB(....)'
KIKPPP1$.txt * - KICKS system file for transaction codes
KIKPCT1$.txt * - KICKS system file for transaction codes
* CAUTION: please copy only the line with "RRPC"/"RRPCALC" into each of your KICKS files



- for COBOL, any book or website will do;

- for CICS I've used Doug Lowe's classic "Cics for the Cobol Programmer".
For this example, the first part "Part 1: An Introductory Course" suffices.
I own the original books, so I don't know whether they are available on the web. 

- For KICKS installation and operation, see
Moshix - KICKS ( CICS ) for IBM MVS 3.8: https://youtu.be/u_ZSH9OagTM
https://github.com/moshix/kicks
http://www.kicksfortso.com/User's%20Guide%201.5.0/KooKbooK/02/index.htm 
http://www.kicksfortso.com/User's%20Guide%201.5.0/index.html?Examples.shtml
"Overview" at http://www.kicksfortso.com/
http://www.kicksfortso.com/User's%20Guide%201.5.0/KooKbooK/01/index.htm
