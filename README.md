<html>
    <head>
        <meta charset="utf-8" /> 
        <link rel="stylesheet" href="less4.css" /> 
    </head> 
    <style>
      a:link {   
        color: #33ccff;
      } 
      a:visited {   
        color: #cecece; 
    }   
    a:hover { 
        color: #336666; 
    } 
    a:active {   
        color: #339999; 
    }
    ul { 
        list-style: none; 
    }
    li a { 
        color: #fff; 
        text-decoration: none;
        padding: 4px 7px; 
        width: 120px; 
        background: #0076ba; 
        display: block; 
        border: 1px solid #fff; 
        font-weight: bold; 
    }
    li a:hover { 
        background: #d36800; 
    }
    </style>
    <body> 
        <a id="start"> </a> 
        <ul>
            <li><a href="#p2">К секции p2</a></li>
            <li><a href="#end">В конец документа</a></li> 
        </ul>
        <p id="p1"> 
            <strong>Это текста в секции p1.</strong> Это текста в секции p1. Это
            текста в секции p1. Это текста в секции p1. Это текста в секции p1. Это текста в секции p1.
            Это текста в секции p1. Это текста в секции p1. Это текста в секции p1. Это текста в секции 
            p1. Это текста в секции p1. Это текста в секции p1. Это текста в секции p1. 
            </p> 
            <p id="p2">
                <strong>Это текста в секции p2.</strong> Это текста в секции p2. Это 
                текста в секции p2. Это текста в секции p2. Это текста в секции p2. Это текста в секции p2. 
                Это текста в секции p2. Это текста в секции p2. Это текста в секции p2. Это текста в секции 
                p2. Это текста в секции p2. Это текста в секции p2. Это текста в секции p2. 
            </p> 
            <ul>
                <li><a href="#start">В начало документа</a></li> 
                <li><a href="#p1">В секции p1</a></li> 
            </ul>  
            <a id="end"> </a> 
    </body>                
</html>
