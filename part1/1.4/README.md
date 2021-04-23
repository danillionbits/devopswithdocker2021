sudo docker run -it ubuntu
-> apt-get update && apt-get install -y curl
-> sh -c 'echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;'
-> helsinki.fi


<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html>
<head>
<title>301 Moved Permanently</title>
</head>
<body>
<h1>Moved Permanently</h1>
<p>The document has moved <a href="http://www.helsinki.fi/">here</a>.</p>
</body>
</html>
