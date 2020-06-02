## CryptoGenotyper

Connecting Docker containter and singularity image were created

git clone https://github.com/supark87/CryptoGenotyper.git
mkdir inputfile
cd inputfile
copy files into this inputfile


## Singularity use

singularity pull docker://supark87/cryptogenotyper_version1

singularity run -B $(pwd)/inputfile/://data/inputfile/ cryptogenotyper_version1.simg //data/inputfile/ //data/db_all3 "you email address"

## Docker use

docker pull docker pull supark87/cryptogenotyper_version1

docker run -it -v $(pwd):/data/inputfile/ cryptogenotyper_version1 /data/inputfile/ /data/db_all3 "your email address"

## Github/Gitlab use


typer_test_ver1.py /your_input_directory /your_db_directory "your email"
