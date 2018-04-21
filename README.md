# JavatpointAsPdf
You can download using this bash script pages of javatpoint as pdf

url_prefix='https://www.javatpoint.com/'
url_suffix='java-tutorial' ; Change it to match your start URL
end_string='cpp-vs-java'   ; Change it to match your end URL

From start URL, script will pick the next button URL and before moving to it will download 
the current URL page as PDF; Will downlaod till the end URL;

At present it don't remove clutters before generating pdfs; 

It downlods the pdfs in the same folder in which bash script is present;

do ./bashScriptName to run the script.

it creates 2 extra files 1. temp.html which is just a temp file and you can delete it after task is completed
                         2. totalText.txt, it contains all URL which have been converted to PDF so far
