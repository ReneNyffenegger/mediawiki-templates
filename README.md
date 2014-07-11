# Using templates

    {{Heading1|This is a Heading1}}

    {{Text|1=Foo bar baz}}

    {{Heading2|This is a Heading2}}

    {{SQL|select * from table}}
    
# Creating templates

A *`<span>`* with a css style can be created like so

    <span style='background-color:#ffff00;border:1px solid #eedd00'>Some fixed text <b>{{{1}}}</b></span>


# Inserting vertical bars

Since the `|` has a special function with mediawiki texts, the template [!](https://github.com/ReneNyffenegger/mediawiki-templates/blob/master/!)
can be used to insert a vertical bar: `{{|}}`.
