# Solve the problem for nltk connection error
This is the solution for nltk connection error like:
```
nltk_data] Error loading punkt: <urlopen error [Errno 111] Connection refused>
```

or:
```
LookupError:
**********************************************************************
  Resource punkt not found.
  Please use the NLTK Downloader to obtain the resource:

  >>> import nltk
  >>> nltk.download('punkt')

  For more information see: https://www.nltk.org/data.html
```

## Solution
Using the virtual enviorment as an example:

```bash
git clone https://github.com/chz816/nltk_data.git
mv nltk_data/packages venv/nltk_data
```
