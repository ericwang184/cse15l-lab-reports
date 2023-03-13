# Lab 5 Report
## find -name command line option

The find -name command line option will search for files or subdirectories with a given specific name within the given specific directory. This command line option is case-sensitive

The first example of the find -name command line option is below. 

```
[cs15lwi23aqw@ieng6-203]:skill-demo1-data:522$ find written_2 -name Berlin-WhereToGo.txt
written_2/travel_guides/berlitz2/Berlin-WhereToGo.txt
```

We see that we are trying to find the specific text file called Berlin-WhereToGo.txt in the directory written_2. This will then return the path starting from the searched folder to the text file, if the text file exists. If the text file doesn't exist, then the command option will not return anything. We see this below. 

```
[cs15lwi23aqw@ieng6-203]:skill-demo1-data:523$ find written_2 -name Berlin-WhereTogo.txt
```

Since the file is named Berlin-WhereToGo.txt, -name is case-sensitive and won't recognize Berlin-WhereTogo.txt as Berlin-WhereToGo.txt, therefore not returning anything. 

The second example of the find -name command line option is below. 

```
[cs15lwi23aqw@ieng6-203]:skill-demo1-data:524$ find ./ -name travel_guides
./written_2/travel_guides
```

We see that the find -name command line option can also search for folder names. In this example, we are searching in the current directory for the travel_guides subdirectory. We see that there is a travel_guides subdirectory in the written_2 folder in the current directory, thus 

```
./written_2/travel_guides
```
is returned. 

This function is useful if we want to edit a file, but we don't know how to get to the file. We can find the path to the file using the find -name command line option, then change directory (cd) into that file, then use another command to edit the file. 

I found how to use the find -name command line option [here]https://www.redhat.com/sysadmin/linux-find-command

## 

