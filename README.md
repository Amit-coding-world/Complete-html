#README.MD
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    size of headings- large to small
    <h1>what is your name?</h1>
    <h2>what is your name?</h2>
    <h3>what is your name?</h3>
    <h4>what is your name?</h4>
    <h5>what is your name?</h5>
    <h6>what is your name?</h6>


    container
    <div>this is div block</div><!--block element container-take full width and start with new lines*/ -->
    <div>this is div block</div><!--block element container-take full width and start with new lines*/ -->
    <span>this is span block</span> <!--inline element container-take necessary width and start with same lines*/ -->
    <span>this is span block</span> <!--inline element container-take necessary width and start with same lines*/ -->
    <hr>
    show the code <br>
    <code>&lt;br&gt;</code>

    <hr>
    pre- represents pre-formatted <br>
    <pre> write a>                     what
        Text formatting tags are used to format 
        text or data in HTML documents. You can do 
        certain things like creating italic, bold, and <b>given</b>strong text to 
        make your documen
        t look more attractive
         and understandable
    </pre>
    <hr>
    H2O
    <br>
    H<sub>2</sub>O
    <br>
    A2
    <br>
    A<sup>2</sup>
    <hr>
    <a href=""></a>
    <img src="" alt="">
    <br>
    order list <br> list items-li
    <ol type="I">
        <li>a</li>
        <li>a</li>
        <li>a</li>
        <li>a</li>
        <li>a</li>
        <li>a</li>
    </ol>
    <hr>
    unorder list <br>
    <ul type="">
        <li>a</li>
        <li>a</li>
        <li>a</li>
        <li>a</li>
        <li>a</li>
        <li>a</li>
    </ul>
    <hr>
    <audio src="" controls></audio>
    <video src="" controls height=""></video>

    <hr>
    &br
    <legend>
    <table>
        <tr>
            <th>Col1</th>
            <th>Col2</th>
            <th>Col3</th>
            <th>Col4</th>
        </tr>
        <tr>
            <td>r</td>
            <td>a</td>
            <td>r</td>
            <td>e</td>
        </tr>
        <tr>
            <td>b</td>
            <td>a</td>
            <td>r</td>
            <td>e</td>
        </tr>
    </table>
    </legend>
    <hr>
    <legend>form
    <form action="post">
        <label for="name">name:</label>
        <input type="text" name="username" placeholder="enter your name" id="name"><br> <br>
        <label for="password">password:</label>
        <input type="password" name="password" id="password" placeholder="enter the password" required>
        <br>
        <br>
        <label for="hobby">hobbies</label> <br>
        <input type="checkbox" name="hobbies" id="hobby" value="sports">sports  <br>
        <input type="checkbox" name="hobbies" id="hobby" value="reading">reading <br>
        <input type="checkbox" name="hobbies" id="hobby" value="listen song">listen song <br>
        <br>
        <br>
        
        <label for="gender">gender</label>
        <br>
        <input type="radio" name="gender" id="male" value="male">
        <label for="male">male</label>
        <br>

        <input type="radio" name="gender" id="female" value="female">
        <label for="female">female</label>

        <br>
        <label for="date">DOB</label>
        <input type="date" value="DOB" id="date" name="DOB">
        <br>
        
        <br>
        <label for="country">Country</label>
        <select name="Country" id="country">
            <option value="india">india</option>
            <option value="usa">usa</option>
            <option value="uk">uk</option>

        </select>

        <br>
        <br>

        <label for="file">photo</label>
        <input type="file" name="photo">
        <br>
        <br>
        
        <label for="">Address</label>
        <textarea name="Address" id="" rows="4" cols="50">here enter the parmanetly Address</textarea>
        <br>
        <label for="volume">volumn</label>
        <input type="range" name="volume" min="0" max="100" value="volume" id="volume">
        <br>
        <label for="quantity">choice any number between 1-10:-</label>
        <input type="number" name="quantity" min="1" max="10" id="quantity" >
        <br>
        <input type="search" name="query" placeholder="Search">
        <br>
        <label for="email">email</label>
        <input type="email" name="email" placeholder="Enter Email">
        <br>
        <label for="">linkdin</label>
        <input type="url" name="linkdin" placeholder="Enter URL of linkdin">
        <br>
        <br>
        <div style="padding: 20px;">
        <button type="reset">reset</button>
        <button type="button">button</button>
        <!-- <button type="submit">submit</button> -->
        <input type="submit" value="submit">
        </div>
        
        
    </form>

    </legend>
</body>
</html>