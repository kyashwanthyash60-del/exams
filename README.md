
<html>
<head>
    <title>Registration Form</title>

    <script>
        function Passvalues()
        {
            var name = document.getElementById("name").value;
            var Email = document.getElementById("Email").value;
            var address = document.getElementById("address").value;

            localStorage.setItem("name", name);
            localStorage.setItem("Email", Email);
            localStorage.setItem("address", address);

            return true;
        }
    </script>
</head>

<body>

    <h1>Registration Form</h1>

    <form action="Details.html">

        <fieldset>
            <legend>Registration</legend>

            <label>Name</label>
            <input type="text" id="name"><br><br>

            <label>Email ID</label>
            <input type="text" id="Email"><br><br>

            <label>Address</label>
            <input type="text" id="address"><br><br>

            <button type="submit" onclick="Passvalues()">Submit</button>

        </fieldset>

    </form>

</body>
</html>
