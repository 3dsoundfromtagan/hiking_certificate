# hiking_certificate
0. To get final `.pdf` files, ensure you have [perl](https://strawberryperl.com/) and `latexmk` (see more [here](https://mg.readthedocs.io/latexmk.html)) 
1. Fill the file [input.csv](input.csv) with participants' names;
2. Change the file [spravka_template.tex](spravka_template.tex) in accordance with your hiking data (distance, passes etc.);
3. Run the file [process.py](process.py). It will change the line `\VAR{USER}` with participants' names and make a line of `.pdf` files by their number.
