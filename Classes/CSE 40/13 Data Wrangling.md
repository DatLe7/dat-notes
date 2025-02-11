### Date: 02-7-2025
### Instructor: Alexander Rudnick


## Notes:

### Overview of Challenges
- Attribute value ambiguity
- Name ambiguity
- Data entry errors
- Missing values
- Changing attributes
- Data formatting
- Abbreviations / data truncation



### Data Cleaning
- Data cleaning involves modifying and removing incomplete, incorrectly formatted, irrelevant, or duplicated data.
- It might also entail converting text-based data to numeric values and redesigning features.

### Attribute Value Ambiguity
- Many ways in which values can be ambiguous
**EX**: (strings)
Brown, brown, browne, brownish, dark brown, greenish brown, etc.
**EX**: (numbers/percentages)
25%, 0.25, 25/100, etc.
**EX**: (unknown values)
null, NaN, “”, “N/A”, “unknown”, 0, -1, -3, -9

### Challenges
- Data Entry Errors
- Missing values / nan Values
- Data Formatting
**![http://www.europeword.com/blog/wp-content/uploads/European-Date-Format.gif](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUfgeazcRM7yVQLyj7e-Ark_zxoA6ccPJXB5uAlcEIbR91b3tyFY3G0BhWQl1cPqo3f9nVmel-e_rCycbalmBzjcFKPLTbKFPuPiPOIFb8_1hKHJaAu9rkBUYMKpI5hKer7-9FdGMQ=s2048?key=NzOBz3E0fBjMh4-W9fIs9X8P)**
- Abbreviations / Data Truncation
**![Vocabulary - ESL Forums](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUfbHT22DM2yKh-C_iMYMeoKRioAHp0eCIwzicPEv5kVdy8k8MPDNE1FDaHKMhAHjgwWB9KwkgRJ7vp3C28Yjq_J54G4Ko9HE-e-Yk1Z5_NMpTxFJNMP1QetdC2Cu9A96OqBKLQqtw=s2048?key=NzOBz3E0fBjMh4-W9fIs9X8P)**

### Key Data Types
- Integers (int class)
- Floats (float class)
- Strings (str class)
Data containers:
- Lists
- Dictionaries

Data cleaning involves making them consistent (type conversions, flattening out lists, etc.)
**Integers and Floats**
	pandas.Int64Dtype  (default)
	int, numpy.int8, numpy.int16, numpy.int32, numpy.int64, numpy.uint64, etc.
	pandas.Float64Dtype  (default)
	float, numpy.int8, numpy.int16, numpy.int32, numpy.int64, numpy.uint64, etc.
***Strings***
	pandas.StringDtype 
	string is default type
	str,object*

### String Encoding
- ASCII codes represent characters. Because of technical limitations of computer systems at the time it was invented, ASCII has just 128 characters, which severely limits its scope.
- UTF-8 is a variable-length character capable of encoding all 1,112,064 valid characters using one to four bytes. 

### File Formats 101
Human-readable
	Excel			Theoretically also machine readable but has a lot of edge cases
	PDF			Easy for humans to read; hard to extract data consistently
	Word			Too unconstrained to be useful for representing data consistently
Machine-readable
	Comma-separated values (CSV)		Most basic type, also TSV (tab separated)
	Extensible Markup Language (XML)	Markup language for storing & transporting data; defined by World Wide Web Consortium
	JavaScript Object Notation (JSON)		Clean, easy to parse, most commonly used format

- Translating many common file formats to machine readable data is just a part of life
- Try to avoid it if you can

### GIGO
- In data processing there is a common phrase:
Garbage In, Garbage Out
- It means that your insights, analysis and predictions are only as good as the data your going to use for it

An ideal, high-quality data set is:
- **Accurate**. The data accurately reflects the “real world” or “gold standard.” 
- **Complete**. All relevant entities and properties are known. 
- **Consistent**. The data is consistent across the entire data set. 
- **Relevant**. All of the data pertains to the question or phenomenon being explored.
- **Valid**. The data falls within appropriate ranges, parameters, and formats.
- **Timely**. The data is recent and up-to-date.
- **Uniform**. Units of measure and representations are consistent across the data set.
