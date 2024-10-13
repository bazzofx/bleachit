# 🧹 Scrapex: A Simple Text Cleaner

While studying for bug Bounty I have been trying some new tools, and I came across one called anew from TomNomNom who I am a great fan.
however, I noticed his anew tool was not removing the words that had a space before or after the word, so I gave a go in creating my own variation of the tool which will help me clean up the lists for the subdomains Im harvesting

**Scrapex** is a convenient function written in Zsh that reads text files, removes empty lines, trims whitespace, and combines lines into unique values. Perfect for cleaning up messy text files and ensuring you have a tidy output! ✨

## 📦 Features

- Removes empty lines 📄
- Trims leading and trailing whitespace ✂️
- Combines lines into unique values 🔍
- Easy to use with multiple input files 📂
- Can be used to trim one file or many files

## 🚀 Example 
 To use the scrapex function, simply call it from the terminal and provide one or more text files as arguments. For example:
```
▶ cat file1.txt
Zero
One
Two
Zero
 Zero
     One

▶ cat file2.txt
One
Two
Three
Four

▶ scrapex file1.txt file2.txt
Four
One
Three
Two
Zero
```
## Usage 
```
▶ scrapex file1.txt

▶ scrapex file1.txt file2.txt

▶ scrapex file1.txt file2.txt file3.txt file4.txt

```


## 🛠 Installation

You can install by making the scrape file executable and moving it to your /bin/usr/scrape

```
chmod +x scrapex
cp scrape /usr/bin/scrapex
```

