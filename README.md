# draft-js-resizeable-plugin

Fork of the [`draft-js-resizeable-plugin`](https://github.com/draft-js-plugins/draft-js-plugins/tree/master/draft-js-resizeable-plugin) plugin, with the following differences: 
* remove the max size limitation based on the editor size (our editor is scrollable, so the image cannot overflow it)
* remove the default size when no size is set on the entity (that way, it assumes the image's full size, instead of setting it to 40% or 40px).
