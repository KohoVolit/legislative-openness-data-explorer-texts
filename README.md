# Legislative Openness Data Explorer - texts
The texts for each language versions are in their own directories named by [https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes](ISO 639-1 codes). The texts are orginized be their respective page of the website.

	/
    	cs/
        	...
        en/
        	about/
            best-practices/
            ...
        ...

Note: **All editing described below requires writing rights for this GitHub project!**

## Editing markdown (.md) files
These files may be easily edited using prose.io application here: [http://prose.io/#KohoVolit/legislative-openness-data-explorer-texts](http://prose.io/#KohoVolit/legislative-openness-data-explorer-texts)

## Editing comma separated values/CSV (.csv) files
These files may be edited:  
1. directly on GitHub (e.g., [https://github.com/KohoVolit/legislative-openness-data-explorer-texts/edit/master/en/about/texts.csv](https://github.com/KohoVolit/legislative-openness-data-explorer-texts/edit/master/en/about/texts.csv))  
2. using prose.io application ([http://prose.io/#KohoVolit/legislative-openness-data-explorer-texts](http://prose.io/#KohoVolit/legislative-openness-data-explorer-texts))  
3. using OO Calc, Excel or similar spreadsheet tool + synchronizing through Git (requires previous cloning of the project to a local repository)

Note: **Do NOT translate first row and first column of the CSV files**, they contain codes of the texts.

## Best practices - examples
These examples are stored in
	
    /
    	_language-code_/
        	best-practices/
        		examples/
            
and their "master file" (containg weight and categories of the example) is

	/
    	_language-code_/
        	best-practices/
            	examples.csv

### Adding a new best practice example (for English, i.e. 'en')
1. Create a new .md file, e.g. `/en/best-practices/examples/my_new_example.md`
2. Add its name (without .md), weight and categories (to which the new example belongs) into: `/en/best-practices/examples.csv`.  
E.g., by adding a row `my_new_example,5,citizen-participation` to the CSV file.  
More categories for a single example may be added separated by semicolon, e.g. `citizen-participation;accessibility`



            	
