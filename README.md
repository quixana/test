Heading
=======
 
Sub-heading
-----------
 
h3. Traditional html title
 
Paragraphs are separated
by a blank line.
 
Let 2 spaces at the end of a line to do a  
line break
 
Text attributes *italic*,
**bold**, `monospace`.
 
A [link](http://example.com).
<<<   No space between ] and (  >>>
 
Shopping list:
 
  * apples
  * oranges
  * pears
 
Numbered list:
 
  1. apples
  2. oranges
  3. pears
 
The rain---not the reign---in
Spain.

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
