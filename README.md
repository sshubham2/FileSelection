A simple python which will pick latest file using various methods.\

1) By Date - If filename contains date (format - ddmmyyyy), function will return file having most recent date in filename. If multiple files are having most recent date, latest file will be selected using latest create datetime. If multiple files are having same date and same create datetime, file will picked randomly (first element from list).

2) By Create datetime - Latest file will be picked based on file create datetime. If multiple files are having same create datetime, file will picked randomly (first element from list).

3) By Version number - If filename contains version number (integer or float), code will read the number and will return the file having maximum version number. Currently it only supports integer version number and float e.g 1.0, 3.2 etc. module has 2 diffrent function, one when version number is integer and another when version number is decimal.

For creating package, toml file is configured to use hatchling.