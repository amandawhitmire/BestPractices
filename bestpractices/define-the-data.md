---
title: Define the data model
layout: bestpractice
tags:
- access
- data model
- describe
- plan
step:
- describe
- plan
related:
- create-and-document
- create-manage-and
- identify-suitable-repositories
---

## Best Practice
A data model documents and organizes data, how it is stored and accessed, and the relationships among different types of data. The model may be abstract or concrete.

Use these guidelines to create a data model:

1. Identify the different data components- consider raw and processed data, as well as associated metadata (these are called entities)
2. Identify the relationships between the different data components (these are called associations)
3. Identify anticipated uses of the data (these are called requirements), with recognition that data may be most valuable in the future for unanticipated uses
4. Identify the strengths and constraints of the technology (hardware and software) that you plan to use during your project (this is called a technology assessment phase)
5. Build a draft model of the entities and their relations, attempting to keep the model independent from any specific uses or technology constraints.
6. Incorporate intended usage and technology constraints as needed to derive the simplest, most general model possible
7. Test the model with different scenarios, including best- and
8. worst-case (worst-case includes problems such as invalid raw data, user mistakes, failing algorithms, etc)
Repeat these steps to optimize the model

## Description Rationale
Considering and creating the data model helps with data planning and identifies potential problems that future data users might encounter.

## Related Best Practices
- Create and document a data backup policy
- Create, manage, and document your data storage system
- Identify suitable repositories for the data

## Additional Information
Wikipedia: http://en.wikipedia.org/wiki/Data_model
IBM: http://publib.boulder.ibm.com/infocenter/tivihelp/v8r1/index.jsp?topic=/...
Agile Data: http://www.agiledata.org/essays/dataModeling101.html

## Examples
Different types of data model examples can be found here: http://www.databaseanswers.org/data_models/index.htm
