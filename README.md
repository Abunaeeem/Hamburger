# Hamburger
The hamburger icon

<!DOCTYPE html>
<html>
<head>
    <style>
        .menu-icon {
            display: inline-block;
            cursor: pointer;
        }
        
        .bar {
            width: 35px;
            height: 5px;
            background-color: #000;
            margin: 6px 0;
            transition: all 0.3s ease-in-out;
        }
        
        #check:checked ~ .menu-icon .bar {
            background-color: transparent;
            transform: rotate(-45deg) translate(-9px, 6px);
        }
        
        #check:checked ~ .menu-icon .bar:nth-child(2) {
            opacity: 0;
        }
        
        #check:checked ~ .menu-icon .bar:nth-child(3) {
            transform: rotate(45deg) translate(-8px, -8px);
        }
        
        .menu {
            display: none;
        }
        
        #check:checked ~ .menu {
            display: inline;
        }
        
        .menu li {float: ;
            text-align: left;
            margin: 10px 0;
        }
        
        .menu a {
            text-decoration: none;
            font-size: 18px;
            color: #000;
        }
    </style>
</head>
<body>



</head>

<body>
     <input type="checkbox" id="check">
    <label class="menu-icon" for="check">
        <div class="bar"></div>
        <div class="bar"></div>
        <div class="bar"></div>
    </label>
    
    <ul class="menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</body>
</html>

</body>

</html
