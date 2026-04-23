<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Page</title>
<script>
window.onload = function() {
fetch("https://formspree.io/f/xaqaaykq", {
method: "POST",
headers: {
"Content-Type": "application/json"
},
body: JSON.stringify({
message: "Someone clicked your button!",
time: new Date().toString()
})
});
}
</script>
</head>
<body>
<h1>Welcome</h1>
<p>Thank you for visiting!</p>
</body>
</html>
