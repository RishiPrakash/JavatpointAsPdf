# JavatpointAsPdf
You can download using this bash script pages of javatpoint as pdf

```
url_prefix='https://www.javatpoint.com/'
url_suffix='java-tutorial' ; Change it to match your start URL
end_string='cpp-vs-java'   ; Change it to match your end URL
```

## How it works
From start URL, script will pick the next button URL and before moving to it will download 
the current URL page as PDF; Will downlaod till the end URL;

## Progress so far
* At present it don't remove clutters before generating pdfs; 
* It downlods the pdfs in the same folder in which bash script is present;

## How to run
do ./bashScriptName to run the script.

### Something to take care
it creates 2 extra files 1. temp.html which is just a temp file and you can delete it after task is completed
                         2. totalText.txt, it contains all URL which have been converted to PDF so far

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
