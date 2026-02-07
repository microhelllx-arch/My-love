<!DOCTYPE html>
<html>
<head>
<title>For My Love NANDHA ❤️</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: black;
    color: white;
    text-align: center;
    overflow: hidden;
}

/* First screen */
#startScreen {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background: black;
}

button {
    padding: 15px 30px;
    font-size: 20px;
    background: red;
    color: white;
    border: none;
    border-radius: 30px;
}

/* Love page */
#lovePage {
    display: none;
    padding: 20px;
}

/* Background image */
.bg {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: url('love.jpg') center/cover no-repeat;
    opacity: 0.4;
    z-index: -1;
}

/* Hearts animation */
.heart {
    position: fixed;
