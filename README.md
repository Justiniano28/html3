function toCamelCase (str) {

Let strArray;

if (str.indexOf ("- ") !== -1){

strArray = str.split (" -
)
else {
strArray =str.split ("_")



let ccString = str[0];


for (leti = = 1; i < strArray. length; i++){

ccString += capitalize (strArray [i]) ;



return ccString;



let capitalize = (str) = {
return str[0]. toUpperCase () str.slice (1) ;


