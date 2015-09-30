<!-- .slide: data-menu-title="Creating a TOC Slide - Source" -->

## Creating a TOC slide

**How to**
* The first line must be `<!-- .element: class="toc" -->` followed by a blank line.  
* The title must be annotated with `###`.
* Highlight the current element in the list by adding `<!-- .element: class="current-item" -->` after the list item.

```
<!-- .element: class="toc" -->
<!-- .slide: data-menu-title="Creating a TOC Slide - Example" -->

### Topic slides for sections

* current section<!-- .element: class="current-item" -->
* next section
* another section
* and one more

<i class="fa fa-cloud fa-lg"></i>
```

**Notes**
* You can use ordered or unordered lists.
* You can include icons or images as a graphic.
