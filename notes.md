<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="main.js" defer></script>
    <link rel="stylesheet" href="main.css">
    <title>Document</title>
</head>
<body>
            <!-- Main Container -->
    <div class="main-container">
        <!-- Form -->
        <form id="calc_form" name="calculation">
            <input type="text" name="viewer" class="viewer">
        </form> <!-- End of Form -->
        
        <!-- Table -->
        <table class="table">
            <tr>
                <td colspan="2"><input type="button" class="button zero-btn" value="0"></td>
                <td><input type="button" class="button" value="."></td>
                <td><input type="button" class="button equal" value="="></td>
            </tr>
            
            <tr>
                <td><input type="button" class="button" value="+"></td>
                <td><input type="button" class="button" value="-"></td>
                <td><input type="button" class="button" value="*"></td>
                <td><input type="button" class="button" value="/"></td>
            </tr>

            <tr>
                <td><input type="button" class="button" value="7"></td>
                <td><input type="button" class="button" value="8"></td>
                <td><input type="button" class="button" value="9"></td>
                <td><input type="button" class="button back" value="<"></td>
            </tr>

            <tr>
                <td><input type="button" class="button" value="4"></td>
                <td><input type="button" class="button" value="5"></td>
                <td><input type="button" class="button" value="6"></td>
                <td><input type="button" class="button clear" value="C"></td>
            </tr>

            <tr>
                <td><input type="button" class="button" value="1"></td>
                <td><input type="button" class="button" value="2"></td>
                <td><input type="button" class="button" value="3"></td>
                <td rowspan="5"><input type="button" class="button equal" value="="></td>
            </tr>

            <!-- <tr>
                <td colspan="2"><input type="button" class="button zero-btn" value="0"></td>
                <td><input type="button" class="button" value="."></td>
            </tr> -->
        </table>  <!-- End of Table -->

    </div>  <!-- End of Main Container -->
        
</body>
</html>