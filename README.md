# assignment-2-validation-js-ShivaniSakpal
assignment-2-validation-js-ShivaniSakpal created by GitHub Classroom
function validate()
        {
            
              var x = document.forms["myform"]["uname"].value;
              if (x == "")
              {
                alert("Name must be filled out");
                return false;
              }
              var y = document.forms["myform"]["password"].value;
              if (y == "")
              {
                alert("Password must be filled out");
                return false;
              }
            
        }
function validateForm()
        {
              var pn = document.forms["myForm"]["pnum"].value;
              if (pn == "" || pn.length!=10)
              {
                alert("Phone number must be of atleast 10 digits");
                return false;
              }
        }
        
