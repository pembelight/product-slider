# product-slider

Product-slider for miniShop2 (Modx) deversifies the presentation of products and gives a possibility to relate them in one slider. In the result you will have a slider with a previews of related goods 
What we need:
1. To download and to integrate Owl Carousel from https://owlcarousel2.github.io/OwlCarousel2/ accroding to your web-site style.
2. To use msProducts where:<br/>
   &tpl=`your tpl name` // the chunk, where you place owl-item<br/>
   &limit=`your item limit` // the quantity of visible owl-items<br/>
   &parents=`your id` // the id of parent-page<br/>
   &resources=`id` // to choose the products by id<br/>
   &includeThumbs=`45x45` // to indicate the sizes of previews<br/>
    &includeTVs=`1` // are optional if you use some tv in tpl<br/>
		&processTvs=`1` // are optional if you use &includeTVs
	  
 3. To insert a link into the div with the class="owl-item" where:<br/>
    href={$id | url} is a link to the related product page<br/>
    src={$thumb} is a source for image preview
