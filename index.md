<html>
<body>
今天是：<span id = 'today'></span>
<br/>
距  --2020年6月24日--  还有<span id = 'count'></span>天！！！
</body>
<script>
var today = document.getElementById('today');
var date = new Date();
today.innerText = date.toLocaleString();
var someday = new Date(2020,5,24);
var days = parseInt((someday - date)/(24*60*60*1000));
var count = document.getElementById('count');
count.innerText = days;
</script>
</html>
