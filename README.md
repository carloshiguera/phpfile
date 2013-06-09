<html>
	<head>
		<title>My Php</title>
	</head>
	<body>
		<div>
			<center>
				<h1>
					My Php
				</h1>
			</center>
		</div>
		<div>
			<?php
$image = imagecreatetruecolor(300, 300);
$red = imagecolorallocate($image, 255, 255, 0);
imagefill($image, 0, 0, $red);

header("Content-type: image/png") ;
imagepng($image);

			?>
		</div>
	</body>
</html>
