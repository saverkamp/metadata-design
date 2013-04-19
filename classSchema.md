### Schema for Aggregation Party

For your crosswalk (draft due 4/29), map your own schema to the class schema below. Include details on how you will normalize your data values (if necessary) to meet the requirements of the target schema. For instance, you may need to trim your creation dates back to only yyyy or replace personal name URIs with string values.  

For the aggregation party (5/6), you will bring 20 of your records transformed from your own schema to the class schema. Serialize your records in a single csv file (element names in the top row as a header, one record per row below). Separate repeated values within a single cell with semicolons.  

We will be trying out some of Viewshare's visualization tools, including the Map View, so I strongly encourage you to include geographic coordinates for any spatial data you may have.  


<table border="1" cellpadding="3">
<tbody>
<tr>
<td><strong><em>REQUIRED</em></strong></td>
</tr>
<tr>
<td><strong>Element</strong></td>
<td><strong>Definition</strong>
<td><strong>Repeatable?</strong></td>
<td><strong>Comments</strong></td>
</tr>
<tr>
<td>dc:title</td>
<td>The title of the resource.</td>
<td align="center">Y</td>
<td></td>
</tr>
<tr>
<td>dc:identifier</td>
<td>A unique reference to the resource within the context of our aggregated class data.</td>
<td align="center">N</td>
<td>The only reason your identifier may duplicate another classmate's is if you are both describing the same resource (ex., ISBN). Please make an effort to create unique identifier</td>
</tr>
<tr>
<td>dc:type</td>
<td>The nature of the resource.</td>
<td align="center">Y</td>
<td>Select value(s) from the DCMI Type Vocabulary.</td>
</tr>
<tr>
<td>dc:publisher</td>
<td>The entity responsible for making the resource available.</td>
<td align="center">N</td>
<td>Normally, this is the name of the organization making the digital resource available. For our purposes, use your own name (or handle, if you don't want your real name out there in public).</td>
</tr>
<tr>
<td>dc:rights</td>
<td>Information about rights held in and over the resource.</td>
<td align="center">N</td>
<td>This should be a brief, free-text statement about rights and permissions regarding the resource (not the metadata!)</td>
</tr>
<tr><td><strong><em>RECOMMENDED</em></strong></td></tr>
<tr>
<td>dc:creator</td>
<td>An entity primarily responsible for making the resource.</td>
<td align="center">Y</td>
<td>Use a text string for this value rather than a URI.</td>
</tr>
<tr>
<td>dc:date</td>
<td>The date associated with the creation of the resource.</td>
<td align="center">N</td>
<td>Encode in ISO 8601 for single year only: yyyy. No date ranges--choose a single date.</td>
</tr>
<tr>
<td>dc:description</td>
<td>An account of the resource.</td>
<td align="center">N</td>
<td></td>
</tr>
<tr>
<td>dc:subject</td>
<td>The topic of the resource</td>
<td align="center">Y</td>
<td>Unless part of a subject string, enter geographic or temporal subjects in dc:spatial and dc:temporal.</td>
</tr>
<tr>
<td>dc:language</td>
<td>A language of the resource</td>
<td align="center">Y</td>
<td>Use the full text of the language, not the code.</td>
</tr>
<tr><td><strong><em>OPTIONAL</em></strong></td></tr>
<tr>
<td>dc:contributor</td>
<td>An entity responsible for making contributions to the resource.</td>
<td align="center">Y</td>
<td>Use a text string for this value rather than a URI.</td>
</tr>
<tr>
<td>dc:spatial</td>
<td>The geographic coverage of the resource.</td>
<td align="center">Y</td>
<td>Include coordinates in local:coordinates</td>
</tr>
<tr>
<td>dc:temporal</td>
<td>The temporal coverage of the resource.</td>
<td align="center">Y</td>
<td>Free-text, may include LC subdivisions, date ranges, etc.</td>
</tr>
<tr>
<td>local:coordinates</td>
<td>Any spatial coverage of the resource expressed in latitude, longitude</td>
<td align="center">Y</td>
<td>Include both latitude and longitude in this format: latitude,longitude</td>
</tr>
<tr>
<td>local:url</td>
<td>The online location of a digital resource</td>
<td align="center">N</td>
<td>If you are describing a resource online, include the URL here. It may be a duplicate of dc:identifier.</td>
</tr>
</table>