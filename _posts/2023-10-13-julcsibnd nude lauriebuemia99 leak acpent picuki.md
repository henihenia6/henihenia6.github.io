<style media='all' type='text/css'>
.bwstoc {
 margin: 10px 0;
 background: #F0F0F0;
 border: 1px solid #ddd;
}
.bwstoc ol, .bwstoc ul {
 margin: 0 0 15px 20px;
 padding: 0;
}
.bwstoc ul {
 list-style: disc;
}
.bwstoc ol li, .bwstoc ul li {
 font-size: 95%;
 padding: 5px 10px 0 0;
 margin: 0 0 0 30px;
}
.bwstoc a {
 text-decoration: none;
}
.bwstoc a:hover {
 text-decoration: underline;
}
.bwstoc .bwstocHeader {
 font-weight: bold;
 font-size: 100%;
 position: relative;
 outline: none;
 border: none;
 padding: 5px 15px 5px 5px;
 margin: 5px 10px;
}
.bwstoc .bwstocHeader a {
 text-decoration: none;
 cursor: pointer;
}
.bwstoc .bwstocHeader a:hover {
 text-decoration: underline;
}
</style>
<!-- Blogger TOC -->
<script type='text/javascript'>
//<![CDATA[
function bwstoc() {
 var bwstoc = i = headinglength = getheading = 0;
 headinglength = document.getElementById("post-toc").querySelectorAll("h2, h3, h4").length;
 if (headinglength > 1) { 
 // Hanya Tampil Jika Ditemukan Minimal 2 Heading
 for (i = 0; i < headinglength; i++) {
 getheading = document.getElementById("post-toc").querySelectorAll("h2, h3, h4")[i].textContent;
 var bws_1 = getheading.replace(/[^a-z0-9]/gi," ");
 var bws_2 = bws_1.trim();
 var getHeadUri = bws_2.replace(/s/g, "_");
 document.getElementById("post-toc").querySelectorAll("h2, h3, h4")[i].setAttribute("id", getHeadUri);
 bwstoc = "<li><a href='#" + getHeadUri + "'>" + getheading + "</a></li>";
 document.getElementById("bwstoc").innerHTML += bwstoc;
 }
 } else { document.write("<style>.bwstoc{display:none !important;visibility:hidden !important;width:0 !important;height:0 !important;}</style>"); }
}
function bwstocShow() {
    var bwstocBtn = document.getElementById('bwstoc');
 var bwstocWrapID = document.getElementById('bwstocwrap');
 var bwstocLink = document.getElementById('bwstocLink');
    if (bwstocBtn.style.display === 'none') {
        bwstocBtn.style.display = 'block';
 bwstocWrapID.style.display = 'block';
 bwstocLink.innerHTML = 'Content :';
 
    } else {
        bwstocBtn.style.display = 'none';
 bwstocWrapID.style.display = 'inline-block';
 bwstocLink.innerHTML = 'Content :';
    }
}
//]]>
</script>
<noscript><style media='all' type='text/css'>#bwstocwrap,.bwstoc{display:none !important;visibility:hidden !important;width:0 !important;height:0 !important;}</style></noscript>
<br />
<div id='post-toc'><br />



<div id='bwstocwrap' class='bwstoc' style='display:inline-block;'><div class='bwstocHeader'><a id='bwstocLink' onclick='bwstocShow()'>Content :</a></div><ul id='bwstoc' style='display:none'></ul></div>


<!--tuliskonten disini 🥰🥰🥰🥰🥰🥰 -->

<style>
/* Image Slider by www.ferisp.com */
.sliderBox .sliderContainer{display:flex;width:100%;white-space:nowrap;flex-direction:row;overflow:auto;scroll-behavior:smooth}
.sliderBox .sliderContent img{margin-right:20px;border-radius:3px;max-width:720px;max-height:225px;scroll-snap-align:start;box-shadow:0 0 10px 0 rgba(0,0,0,.2)}
@media screen and (max-width:500px){.sliderBox .sliderContent img{width:300px}}
::-webkit-scrollbar{height:8px}
::-webkit-scrollbar-thumb,::-webkit-scrollbar-thumb:hover{background:#ccc;border-radius:50px}
/* Dark Mode */
.drK ::-webkit-scrollbar-thumb,.drK ::-webkit-scrollbar-thumb:hover{background:#666}</style>
<div class="sliderBox">
  <div class="sliderContainer">
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
<div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
<div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
<div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
  </div>
</div>

<style type="text/css">
.bcd140526_post_feed li.item {
    display: block;
    clear: both; 
height: auto;
    margin: 15px 0 0 0;
    padding: 15px 0 0 0;
    border-top: 1px dotted #BBB;
}
.bcd140526_post_feed ul {
    margin: 0;
 height: auto;
    padding: 0;
}
.bcd140526_post_feed li.item.item-0 {
    margin: 0;
    padding: 0; 
height: auto;
    border: none;
}
.bcd140526_post_feed li.item h3.title {
    display: block;
 height: auto;
    margin: 0 0 5px 0;
}

.bcd140526_post_feed li.item div.meta {
    font-size: 11px;
 height: auto;
    color: #999;
	margin: 0 0 5px 0;
}
.bcd140526_post_feed li.item div.meta .meta-item {
    display: inline-block;
	*display: inline;
	zoom: 1;
    margin: 0 1em 0 0;
 height: auto;
}
.bcd140526_post_feed li.item p.snippet {
    line-height: 1.5em;
	margin: 0;
 height: auto;
}
.bcd140526_post_feed.list a.thumbnail {
    margin: 0 7px 7px 0;
    float: left;
    display: block;
    line-height: 1; 
height: auto;
	/*
    width: 48px;
    height: 48px;
	*/
    overflow: hidden;
    position: relative;
}
.bcd140526_post_feed.list a.thumbnail img {
    width: auto;
    height: auto;
}
.bcd140526_post_feed li.item a.cate {
    display: block;
    margin: 0 0 5px 0;
 height: auto;
}
div.bcd140526_post_feed.column a.thumbnail {
    display: block;
    width: 100%;
    line-height: 1;
    margin: 0 0 5px 0; 
height: auto;
}
div.bcd140526_post_feed.column a.thumbnail img {
    width: 100%;
    height: auto;
}
</style>
<style>
table {
  border-collapse: collapse;
  border-spacing: 0;
  margin: 2rem 0;
  width: 100%;
}
th, td {
  padding: 1rem 1.5rem;
  text-align: left;
}
th {
  background-color: #008c5f; /* header background color */
  color: #fff; /* header text color */
  font-weight: 600;
}
tr {
  padding: 0;
}
td {
  vertical-align: middle;
}
tr:nth-child(even) td {
  background-color: rgba(0, 0, 0, .075); /* striped background color */
}
@media screen and (max-width: 640px) {
  thead, th {
    display: none;
  }
  tr, td {
    display: block;
  }
  tr {
    border: 1px solid rgba(0, 0 , 0 ,.15);
    margin-bottom: 2rem;
  }
  tr:last-child {
    margin-bottom: 0;
  }
  tr:nth-child(even) td {
    background-color: transparent;
  }
  td {
    clear: both;
    text-align: right;
  }
  td:before {
    content: attr(data-label)': ';
    float: left;
    font-weight: bold;
    margin-right: 1rem;
  }
}</style>
<table cellpadding="0" cellspacing="0" style="text-align: left;"><tbody> 
<tr> <th>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</th> <th>

<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.xselebgram.xyz" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>


</th> </tr> 
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.xcelebgram.my.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.teteh-ingga.my.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.ingganinggra.my.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.sisalindri.my.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.sawdogong.my.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.dukuhmaga.my.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.xcelebgram.my.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
<tr> <td>
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
</td> <td>
<script numberofposts="1" label="none" display="vertical" boxrounding="5" boxbackground="#3d3d3d" boxpadding="5" lineheight="1.2" borderwidth="3" borderstyle="outset" bordercolor="#474747" showimage="none" showtitle="left" titlefont="Inherit" titlesize="18" boldtitle="true" titlecolor="#fdff6b" showinfo="none" showlabels="left" numberoflabels="20" excerptlength="0" textfont="Inherit" textsize="14" textcolor="#e3e3e3" blogurl="https%3A%2F%2Fwww.qpwoeiruty.biz.id" async src="https://cdn.jsdelivr.net/gh/bloggerwidgets/scripts@1.1.7/randomposts.js"></script>

</td> </tr>
</tbody></table>
<style>
/* Image Slider by www.ferisp.com */
.sliderBox .sliderContainer{display:flex;width:100%;white-space:nowrap;flex-direction:row;overflow:auto;scroll-behavior:smooth}
.sliderBox .sliderContent img{margin-right:20px;border-radius:3px;max-width:720px;max-height:225px;scroll-snap-align:start;box-shadow:0 0 10px 0 rgba(0,0,0,.2)}
@media screen and (max-width:500px){.sliderBox .sliderContent img{width:300px}}
::-webkit-scrollbar{height:8px}
::-webkit-scrollbar-thumb,::-webkit-scrollbar-thumb:hover{background:#ccc;border-radius:50px}
/* Dark Mode */
.drK ::-webkit-scrollbar-thumb,.drK ::-webkit-scrollbar-thumb:hover{background:#666}</style>
<div class="sliderBox">
  <div class="sliderContainer">
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
<div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
<div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      <script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
<div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>

    </div>
    <div class="sliderContent">
      
<script type="text/javascript">
/*
Blogger Random - Recent - Specific Label Posts Widget - All in One Post Feed Widget
Link: https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/
Author: Tien Nguyen
Version: 1.7
*/
var bcd140526_show_thumbnail = true;/*bcd140526_show_thumbnail*/
var bcd140526_show_label = false;/*bcd140526_show_label*/
var bcd140526_show_comment_numbers = false;/*bcd140526_show_comment_numbers*/
var bcd140526_show_date = false;/*bcd140526_show_date*/
var bcd140526_show_author_name = false;/*bcd140526_show_author_name*/
var bcd140526_show_readmore = false;/*bcd140526_show_readmore*/
var bcd140526_show_snippet = true;/*bcd140526_show_snippet*/
var bcd140526_hide_copyright = true;/*bcd140526_hide_copyright*/
var bcd140526_snippet_length = 200;/*bcd140526_snippet_length*/
var bcd140526_post_count = 1;/*bcd140526_post_count*/
var bcd140526_thumbnail_size = 100;// v1.5, only effect with list style/*bcd140526_thumbnail_size*/
var bcd140526_sort_by = 'random'; // latest or random/*bcd140526_sort_by*/
var bcd140526_index_label = '';/*bcd140526_index_label*/
var bcd140526_design_style = 'column';// list or column/*bcd140526_design_style*/
var bcd140526_date_format = 'mm/dd/yyyy';/*bcd140526_date_format*/
var lang_readmore = 'Readmore';/*lang_readmore*/
var HOST = 'https://www.xcelebgram.my.id';/*HOST*/
function bcd140526_bi_script(b){document.write('<script type="text/javascript" src="'+b+'">\x3c/script>')}function bi_date_format(b,a){b=b.split("-");date=new Date(b[0],b[1]-1,b[2].substring(0,2));dd=date.getDate();mm=date.getMonth()+1;yyyy=date.getFullYear();a=a.replace("dd",dd);a=a.replace("mm",mm);return a=a.replace("yyyy",yyyy)}
function bi_get_first_image(b){var a="",d='src="',c='"';index0=b.indexOf("<img ");-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+d.length),-1!=index0&&(a=b.substring(index1+d.length,index2))));""==a&&(d='"',index0=b.indexOf('data-thumbnail-src="'),-1!=index0&&(index1=b.indexOf(d,index0+20),-1!=index0&&(a=b.substring(index0+20,index1))));""==a&&(d='src="',c='"',index0=b.indexOf("<iframe "),-1!=index0&&(index1=b.indexOf(d,index0),-1!=index0&&(index2=b.indexOf(c,index1+
d.length),-1!=index0&&(a=b.substring(index1+d.length,index2),a=a.replace("http://www.youtube.com/watch?v=",""),a=a.replace("http://www.youtube.com/embed/",""),a=a.replace("?rel=0",""),a="http://img.youtube.com/vi/"+a+"/mqdefault.jpg"))));return a}
function bcd140526_bi_jshort(b){var a={},d=/<\S[^>]*>/g;a.id=b.feed.id.$t;key="blog-";index=a.id.indexOf(key);a.id=a.id.substring(index+key.length);a.id=a.id.replace(".comments","");a.cate=[];if("category"in b.feed)for(i=0;i<b.feed.category.length;i++)a.cate[i]=b.feed.category[i].term;a.title="";"title"in b.feed&&(a.title=b.feed.title.$t);a.subtitle="";"subtitle"in b.feed&&(a.subtitle=b.feed.subtitle.$t);a.admin={};a.admin.name="Anonymous";a.admin.uri="";a.admin.avatar="http://img1.blogblog.com/img/anon36.png";
"name"in b.feed.author[0]&&(a.admin.name=b.feed.author[0].name.$t);"uri"in b.feed.author[0]&&(a.admin.uri=b.feed.author[0].uri.$t);"gd$image"in b.feed.author[0]&&"http://img1.blogblog.com/img/blank.gif"!=b.feed.author[0].gd$image.src&&(a.admin.avatar=b.feed.author[0].gd$image.src);a.total_entry=Number(b.feed.openSearch$totalResults.$t);a.start_index=Number(b.feed.openSearch$startIndex.$t);a.item_per_page=Number(b.feed.openSearch$itemsPerPage.$t);a.entry_number=0;"entry"in b.feed&&(a.entry_number=
b.feed.entry.length);a.entry=[];for(i=0;i<a.entry_number;i++){a.entry[i]={};temp={};entry=b.feed.entry[i];temp.id=entry.id.$t;key="post-";index=temp.id.indexOf(key);temp.id=temp.id.substring(index+key.length);temp.published="";"published"in entry&&(temp.published=entry.published.$t);temp.cate=[];if("category"in entry)for(j=0;j<entry.category.length;j++)temp.cate[j]=entry.category[j].term;temp.title="";"title"in entry&&(temp.title=entry.title.$t);temp.content="";"content"in entry&&(temp.content=entry.content.$t);
temp.summary="";"summary"in entry&&(temp.summary=entry.summary.$t);""==temp.summary&&(temp.summary=temp.content.replace(d,""));""==temp.content&&(temp.content=temp.summary);temp.link="";temp.reply_label="comments";if("link"in entry)for(j=0;j<entry.link.length;j++)"alternate"==entry.link[j].rel&&(temp.link=entry.link[j].href),"replies"==entry.link[j].rel&&(temp.reply_label=entry.link[j].title);temp.author={};temp.author.name="Anonymous";temp.author.uri="";temp.author.avatar="http://img1.blogblog.com/img/anon36.png";
a0=entry.author[0];"name"in a0&&(temp.author.name=a0.name.$t);"uri"in a0&&(temp.author.uri=a0.uri.$t);"gd$image"in a0&&"http://img1.blogblog.com/img/blank.gif"!=a0.gd$image.src&&(temp.author.avatar=a0.gd$image.src);temp.thumbnail="";"media$thumbnail"in entry&&(temp.thumbnail=entry.media$thumbnail.url);temp.reply_number=0;"thr$total"in entry&&(temp.reply_number=Number(entry.thr$total.$t));temp.reply_label=temp.reply_label.replace(temp.reply_number+" ","");temp.reply_to="";temp.reply_json="";temp.reply_title=
"";"thr$in-reply-to"in entry&&(temp.reply_to=entry["thr$in-reply-to"].href,temp.reply_json=entry["thr$in-reply-to"].source,temp.reply_json=temp.reply_json.replace("/default/","/summary/"),temp.reply_json+="?alt=json-in-script");temp.pid="";if("gd$extendedProperty"in entry)for(j=0;j<entry.gd$extendedProperty.length;j++)"blogger.itemClass"==entry.gd$extendedProperty[j].name&&(temp.pid=entry.gd$extendedProperty[j].value);temp.pid=temp.pid.replace("pid-","");a.entry[i]=temp}return a}
"undefined"==typeof jquery_included&&(jquery_included=!1);
function jquery_init(){if("undefined"==typeof jQuery){if(!jquery_included){jquery_included=!0;var b=document.createElement("script");b.setAttribute("src","http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js");b.setAttribute("type","text/javascript");document.getElementsByTagName("head")[0].appendChild(b)}setTimeout(function(){jquery_init()},50)}else $('link[href*="font-awesome.css"]').length||(b=document.createElement("link"),b.setAttribute("href","http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"),
b.setAttribute("rel","stylesheet"),document.getElementsByTagName("head")[0].appendChild(b))}jquery_init();function echo(b){document.write(b)}
function bcd140526_show(b){b=bcd140526_bi_jshort(b);var a="";if(b.total_entry){a+='<div class="bcd140526_post_feed '+bcd140526_design_style+" "+(bcd140526_show_thumbnail?"thumb":"no-thumb")+'"><ul>';for(var d=0;d<b.total_entry&&d<bcd140526_post_count;d++){p=b.entry[d];a+='<li class="item item-'+d+'">';p.thumbnail||(p.thumbnail=bi_get_first_image(p.content));if(bcd140526_show_thumbnail&&p.thumbnail){if("column"===bcd140526_design_style){var c=p.thumbnail;-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/",
"/s1600/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s1600-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."))}else c=p.thumbnail,-1!=c.indexOf("/s72-c/")?c=c.replace("/s72-c/","/s"+bcd140526_thumbnail_size+"-c/"):-1!=c.indexOf("=s72-c")?c=c.replace("=s72-c","=s"+bcd140526_thumbnail_size+"-c"):-1!=c.indexOf("youtube.com")&&-1!=c.indexOf("/default.")&&(c=c.replace("/default.","/mqdefault."));p.thumbnail=c;a+='<a class="thumbnail" style="width:'+
bcd140526_thumbnail_size+"%;height:"+bcd140526_thumbnail_size+'%;" href="'+p.link+'"><img src="'+p.thumbnail+'"/></a>'}a+='<div class="item-body">';bcd140526_show_label&&"undefined"!=typeof p.cate[0]&&(a+='<a class="cate" href="'+HOST+"/search/label/"+p.cate[0]+'">'+p.cate[0]+"</a>");a+='<h3 class="title"><a href="'+p.link+'">'+p.title+"</a></h3>";if(bcd140526_show_author_name||bcd140526_show_comment_numbers||bcd140526_show_date)a+='<div class="meta">',bcd140526_show_author_name&&(a+='<span class="meta-item author-name"><i class="fa fa-user"></i> '+
p.author.name+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item comment-number"><i class="fa fa-comment"></i> '+p.reply_number+"</span>"),bcd140526_show_comment_numbers&&(a+='<span class="meta-item date-time"><i class="fa fa-clock-o"></i> '+bi_date_format(p.published,bcd140526_date_format)+"</span>"),a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';
bcd140526_show_snippet&&(p.summary.length>bcd140526_snippet_length&&(p.summary=p.summary.substring(0,bcd140526_snippet_length)+"..."),bcd140526_show_readmore&&(p.summary+=' <a href="'+p.link+'#more">'+lang_readmore+"</a>"),a+='<p class="snippet">'+p.summary+"</p>");a+='<div style="clear:both!important;float:none;!important;line-height:0!important"></div></div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>';a+="</li>"}a+="</ul>";bcd140526_hide_copyright||(a+=
'<div style="clear:both!important;float:none;!important;line-height:0!important"></div><a target="_blank" class="copyright" href="https://sneeit.com/blogger-random-recent-specific-label-posts-widget-all-in-one-post-feed-widget/" style="font-size: 11px!important;text-align:right;visibility: visible;!important;text-indent:0!important;height:auto!important;width:100%!important;position:static!important;color:#999!important;display:block!important;opacity:1!important;">BloggerWidget</a>');a+='</div><div style="clear:both!important;float:none;!important;line-height:0!important"></div>'}else a+=
"<p><em>Have no posts</em></p>";echo(a)}
function bcd140526_main(b){"random"==bcd140526_sort_by?(b=bcd140526_bi_jshort(b),rand=Math.floor(Math.random()*b.total_entry+1),rand+bcd140526_post_count>b.total_entry&&(rand=b.total_entry-bcd140526_post_count+1),1>rand&&(rand=1),b=HOST+"/feeds/posts/default",bcd140526_index_label&&(b+="/-/"+encodeURIComponent(bcd140526_index_label)),b+="?alt=json-in-script&max-results="+bcd140526_post_count+"&start-index="+rand+"&callback=bcd140526_show",bcd140526_bi_script(b)):bcd140526_show(b)}
var script_url=HOST+"/feeds/posts/default";bcd140526_index_label&&(script_url+="/-/"+encodeURIComponent(bcd140526_index_label));script_url+="?alt=json-in-script";script_url="random"==bcd140526_sort_by?script_url+"&max-results=0":script_url+("&max-results="+bcd140526_post_count);script_url+="&callback=bcd140526_main";bcd140526_bi_script(script_url);

</script>
    </div>
  </div>
</div>

<script>bwstoc();</script>
</div>

