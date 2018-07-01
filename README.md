# jQueryAjax
This is how we start writing Ajax In Jquery.
# 3 ways of writing Ajax.
There are 3 ways to write ajax in jquery. They are GET, POST and AJAX.

$.POST("the_page_name", Data, callback funciton);

$.GET("the_page_name", Data, callback funciton);

$.ajax(
type : 'post/get',
url : "the_page_name",
data : {name : value // as pair},
success : function(feedback){
}
);
