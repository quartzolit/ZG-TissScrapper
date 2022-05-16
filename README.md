# ZG-TissScrapper

This script intends to download content from ANS (Agencia Nacional de Saude) website.
Focusing on TISS archives. This project download files from the recent Version of TISS, and ANS Error table.
In addition, we scrapped data from TISS history version, getting its Competence, Publication, and Begin of
Validity.

In order to accomplish every task, we use HttpBuild-NG to parseHTML pages, we also use Jsoup,
opencsv, and http Download to collect the data and download it to downloads's folder.