<html>
    <head>
    <title>student registration form</title>
    <link rel="stylesheet" href="studentreg.css">    
    <script src="student reg.js"></script>    
    </head>
    <body>
        <form name="regform"><center>
            <table id="tablecss"></center>
                <tr>
                     <td colspan=20><center><font size=4><b>Student Registration Form</b></font></center> </td>
                </tr>
                <tr >
                    <td>Name</td>
                    <td><input type="text" name="name" id="name" size="30" onchange="storename(event)"></td>
                </tr>
                <tr>
                    <td>Father Name</td>
                    <td><input type="text" name="fathername" id="fathername" size="30" onchange="storefathername(event)"></td>
                </tr>
                <tr>
                    <td>gender</td>
                    <td><input type="radio" name="gender" value="male" size="10" onclick="storegender(event)">Male
                    <input type="radio" name="gender" value="Female" size="10" onclick="storegender(event)">Female
                    <input type="radio" name="gender" value="Other" size="10" onclick="storegender(event)">Other</td>
                </tr>
                <tr>
                    <td>Course</td>
                    <td><select name="Course" onclick="storecourse(event)">
                    <option value=""> select</option>
                    <option value="B.Tech">B.TECH</option>
                    <option value="MCA">MCA</option>
                    <option value="MBA">MBA</option>
                    <option value="MTECH">MTECH</option>
                    </select></td>
                </tr>
                <tr>
                    <td>EmailId</td>
                    <td><input type="text" name="emailid" id="emailid" size="30" onchange="storeemailid(event)"></td>
                </tr>
                <tr>
                    <td>DOB</td>
                    <td><input type="date" name="dob" id="dob" size="30" onchange="storedob(event)"></td>
                </tr>
                <tr>
                    <td>MobileNo</td>
                    <td><input type="number" name="mobileno" id="mobileno" size="30" onchange="storemobileno(event)"></td>
                </tr>
                <tr>
                    <td>dno</td>
                    <td><input type="number" name="dno" id="dno" size="30" onchange="storedno(event)"></td>
                </tr>
                <tr>
                    <td>streetname</td>
                    <td><input type="text" name="streetname" id="streetname" size="30" onchange="storestreetname(event)"></td>
                </tr>
                <tr>
                    <td>location</td>
                    <td><input type="text" name="location" id="location" size="30" onchange="storelocation(event)"></td>
                </tr>
                <tr>
                    <td>district</td>
                    <td><input type="text" name="district" id="district" size="30" onchange="storedistrict(event)"></td>
                </tr>
                <tr>
                    <td>state</td>
                    <td><input type="text" name="state" id="state" size="30" onchange="storestate(event)"></td>
                </tr>
                <tr>
                    <td>country</td>
                    <td><input type="text" name="country" id="country" size="30" onchange="storecountry(event)"></td>
                </tr>
                <tr>
                    <td>pincode</td>
                    <td><input type="number" name="pincode" id="pincode" size="30" onchange="storepincode(event)"></td>
                </tr>
                <tr>
                    <td><input type="reset" onreset="storereset(event)"></td>
                    <td colspan="2"><button value="Submit Form" onclick="submitform(event)">submit </button></td>    
                </tr>   
            </table>
        </form>
    </body>
 </html>
    
