Markdown Cheatsheet<a name="TOP"></a>
===================
## headings and text ##

# Heading 1 #

    Markup :  # Heading 1 #

## Heading 2 ##

    Markup :  ## Heading 2 ##

### Heading 3 ###

    Markup :  ### Heading 3 ###

#### Heading 4 ####

    Markup :  #### Heading 4 ####

Common text

    Markup :  Common text

*Emphasized text*

    Markup :  *Emphasized text*

~~Strikethrough text~~

    Markup :  ~~Strikethrough text~~

**Strong text**

    Markup : **Strong text**

***Strong emphasized text***

    Markup :  ***Strong emphasized text***


`code()`

    Markup :  `code()`

```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

    Markup : ```javascript
             ```

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

~~~
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2
~~~    

## Links ##

[Named Link](http://www.google.com/ "Named link title") or <http://example.com/>

    Markup :  [Named Link](http://www.google.com/ "Named link title") 
    or
    Markup : <http://google.com/>

[Heading-1](#heading-1 "Goto heading-1")
    
    Markup: [Heading-1](#Deading-1 "Goto Heading-1")

## Tables ##

Table, like this one :

First Column  | Second Column
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Column  | Second Column
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

Adding a pipe `|` in a cell :

First Column  | Second Column
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

```
First Column  | Second Column
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \|
```
Left, right and center aligned table

Left aligned Column | Right aligned Column | Center aligned Column
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

```
Left aligned Column | Right aligned Column | Center aligned Column
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```
