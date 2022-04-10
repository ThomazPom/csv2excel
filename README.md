# csv2excel
.NET command line tool to convert delimited files to Excel format (xls/xlsx) without Excel having to be installed.

The only required parameter is the input file to convert.

csv2excel.exe -i input.csv

All command line options:

i = the path to the input file to convert

o = the path of the output file (path\filename.ext)
    if outputfile isn't specified, it will be set to the same as the input file with the new extension
    
c = the delimiter separating columns of input file
    default delimiter is commma (,)
    
l = the delimiter separating lines of input file
    default delimiter is carriage return line feed (\r\n)
    
f = the format for the output file [xls|xlsx]
    default format is Excel Open XML (xlsx)

t = force all cells in the output worksheet to be of type Text
    default behavior is to insert as Numbers/Dates (in a General cell) if detected
	
v = increase debug message verbosity

h = show command line options


Download the executable here: [bin/Release/csv2excel.exe](https://github.com/nmolinos/csv2excel/raw/master/csv2excel/bin/Release/csv2excel.exe)
