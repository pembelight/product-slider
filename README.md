# product-slider

Product-slider for miniShop2 (Modx) deversifies the presentation of products and gives a possibility to relate them in one slider. In the result you will have a slider with a previews of related goods 
What we need:
1. To download and to integrate Owl Carousel from https://owlcarousel2.github.io/OwlCarousel2/ accroding to your web-site style.
2. To use msProducts where:
   &tpl=`your tpl name` // the chunk, where you place owl-item
   &limit=`your item limit` // the quantity of visible owl-items
   &parents=`your id` // the id of parent-page
   &resources=`id` // to choose the products by id
   &includeThumbs=`45x45` // to indicate the sizes of previews
    &includeTVs=`1` // are optional if you use some tv in tpl
		&processTvs=`1` // are optional if you use &includeTVs
	  &tvPrefix=``   // are optional
 3. To insert <a href="{$id | url}"><img src="{$thumb}" alt=""></a> into the div with the class="owl-item" where:
    {$id | url} is a link to the related product page
    {$thumb} is a source for image preview
