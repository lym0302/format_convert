# format_convert


~~~python
python format_convert.py -I ./data/ -O ./output/
python format_convert.py -i ./data/aa.wav -O ./output/
~~~

# Slice the audio
### Please note that the output folder need to be create before running
~~~python
### If processing a folder. slice to 5000ms(5s) and sliding window is 5000ms(5s)
python cut.py -I "path of input folder" -O "path of output folder" -l 5000 -w 5000

### if input a file
python cut.py -i "path of input file" -O "path of output folder" -l 5000 -w 5000
~~~


## Some packages need to be installed

~~~bash
./install.sh
~~~
