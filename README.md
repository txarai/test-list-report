# test-list-report
Convert the cvs list file to  report file by using latex environment

 README:

    list_report.py: make report for "kaitsu" list.


     usage: list_repo.py [-h] [-f FILENAME] [-o OFILE] [-c CONF] [-v] [-d] [-n]
			[-O] [-m] [-x] [-D]

  optional arguments:
    -h, --help            show this help message and exit
    -f FILENAME, --filename FILENAME
			  Read filename
    -o OFILE, --out OFILE
			  Output filename
    -c CONF, --conf CONF  Read conf FILE
    -v, --verbose         verbose mode
    -d, --date            print DATE (YYYY/MM/DD)
    -n, --new             new mode
    -O, --old             old mode
    -m, --make            Make Top LaTeX File
    -x, --exec            Execute Latex and dvi2pdf
    -D, --debug           debug mode


INPUT list:
   CSV File:
   Date,Week Day,Item,ID,Product,User,Master::Application Co.,,,
