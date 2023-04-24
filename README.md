<html>
    <body>
        <div>
            <h1>crush mo ba ako?</h1>
            <button id="yesButton">Yes</button>
            <button id="no" >No</button>
        </div>

        <style>
            div{
                text-align: center;
                vertical-align: middle;
            }
            #no{
                position: absolute;
            }
        </style>
        <script>
           document.getElementById("yesButton").addEventListener("click",function(){
           alert("yieeeeeeeeeeeeeeeeeeee love u <3"); 
        });
        var b = document.getElementById("no")
        b.addEventListener("click",change);
        function change()   {
            var i = Math.floor(Math.random()*1000)+1;
            var j = Math.floor(Math.random()*700)+1;
            b.style.left = i+ "px";
            b.style.top = j+ "px";
        }
        </script>
    </body>
</html>
