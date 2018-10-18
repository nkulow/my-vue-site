<template>
    <div id="container">
        <div id="navigate">
            <span id="about"> About Me </span> <span>Contact</span>
        
        </div>

        <div id="div-one">
            <p id="title"> I'm Nathan Kulow, a <span id="dev">developer</span>
            currently attending USF in Tampa Florida. </p>
            <br>
            <br>

            <li>
                <font-awesome icon="file" class="file-icon"/>
                <a href="/Users/Kulow/Desktop/my-website2/resume.pdf" download="resume.pdf">
                <i> Download my Resume </i></a>
            </li>

        </div>
        
        
    </div>
</template>


<style>
    #container {
        font-family: 'Open Sans', sans-serif;
    }
    #div-one {
        text-align: left;
        padding-top: 200px;
        padding-right: 400px;
        padding-left: 50px;
        font-size: 40px;
        line-height: 200%;
        font-weight: 400;
        color: rgb(60,60,60);


    }
    #dev {
	    color: #6dd5e0;
    }
    #navigate {
        float: right;
        font-size: 20px;
        color: rgb(60,60,60);
    }
    #about{
        padding-right: 30px;
    }

/* hover over icons for slide out text */
    li {
    overflow: hidden;
    background: #FFFFFF;
    list-style: none;
    white-space:nowrap;
    margin-right: 10px;
    border-radius: 25px;
    display: inline-block;
}
    li a {
        opacity: 0;
        color: #6dd5e0;
        max-width: 0;
        display: inline-block;
        text-decoration: none;
        transition: max-width 1s ease-out .1s, opacity 1s ease-out .1s, color;
    }
        li a:hover {
            color: rgb(60,60,60);
        }
        li a i {
            float:right;
            display: block;
            padding-right: 1em;
            font:1em/1 'rokkitt', sans-serif;
            font-size: 100%;
        }
    .file-icon {
        color: #6dd5e0;
        line-height:1;
        font-size: 60px;
        display: inline-block;
        padding: 10px 10px;
    }
    li:hover {}
        li:hover a {
            opacity: 1;
            max-width: 600px;
            transition: max-width 1s ease-out .1s, opacity 1s ease-out .1s, color .2s;
        }
</style>

