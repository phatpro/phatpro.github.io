---
layout: post
title: '$group aggregate stage'
published: true
---
**$group**
	
    Groups documents by some specified expression and outputs to the next stage a 		document for each distinct grouping. The output documents contain an _id field 		which contains the distinct group by key. The output documents can also contain 	computed fields that hold the values of some accumulator expression grouped by the 	   $group’s _id field. $group does not order its output documents.
    
    The $group stage has the following prototype form:
	
    { $group: { _id: <expression>, <field1>: { <accumulator1> : <expression1> }, ... }}
    
    
