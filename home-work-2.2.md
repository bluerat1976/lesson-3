 <!DOCTYPE html>
<html lang="en">
	<head>
        <style>
		* {
			box-sizing: border-box;
			height: 50px;
			font-size: 16px;
			padding-left: 15px;
			padding-right: 15px;
		}
			.block {
				display: block;
				background-color: rgb(0,154,205);
				border: solid 2px rgb(0,0,238);
				width: 200px;
				padding-top: 15px;
				
			}
			.inline {
				display: inline;
				background-color: rgb(255,255,0);
				border: solid 2px rgb(205,0,0);
				width: 100px;
			}
			.inline-block {
				display: inline-block;
				background-color: rgb(162,205,90);
				border: solid 2px rgb(69,139,0);
				width: 200px;
				padding-top: 15px;
			}
		</style>
    </head>
    <body>
		<p class="block">I am block</p>
		<p class="block">I am block</p>
		<p class="block">I am block</p>
		
		<p class="inline">I am inline</p>
		<p class="inline">I am inline</p>
		<p class="inline">I am inline</p>
		<p class="inline">I am inline</p>
		<p class="inline">I am inline</p>
	<br>	
		<p class="inline-block">I am inline-block</p>
		<p class="inline-block">I am inline-block</p>
		<p class="inline-block">I am inline-block</p>

    </body>
</html>        
             