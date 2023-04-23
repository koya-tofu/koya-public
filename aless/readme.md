# TeX file for ALESS report 

## Functions
- use bibLaTeX to manage cites 
- modify some fields 
- modify name style in Japanese 
  

## Usage
### Installation
Put this in your directory that is same with your report TeX file and add line as: \input{bibaless.tex} <br>
If you have installed TeXLive, it should work with no further installation.

### Some modifications
- Change "cites.bib" in bibaless.tex to your bib file name. 
- Add "langid" field to your references and set it to "japanese" (so add "langid={japanese}" in your bib file). Then change authors'name in bib file like this: <br> 
  author = {Yukawa, H. [湯川秀樹] and Nagaoka, H. [長岡半太郎]}
