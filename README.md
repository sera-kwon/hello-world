# hello-world

<script src=“https://dsjs.org/ds.v4.min.js”></script>

var data = [5, 10, 15, 20, 25, 20, 15, 10, 5];
d3.select(‘body’).selectAll(‘div’)
	.data(dataset)
	.enter()
	.append(‘div’)
	.attr(‘class’, ‘chart’)
	.style(‘height’, function (d) {
	return d*5+’px’;
})

	.chart

{
	display : inline-block;
	width : 25px;
	height : 75px;
	margin-right : 2px;
	background-color : coral;

}
