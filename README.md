<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>job application</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 
    <div class="container">

        <div class="apply_box">
            <h1>job application
                <span class="title_small">(
                    web)</span>
            </h1>
        <form action"">
            <div class="form_container">
                <div class="form_control">
                    <label for="last_name">last name</label>
                        <input id="last_name"
                        name="last_name"
                        placeholder="enter last name..."/>
                </div>
                    <div class="form_control">
                        <label for="email">Email</label>
                        <input type="email"
                        id="email"
                        name="email"
                        placeholder="Enter email...">
                    </div>
                    <div class="form_control">
                        <label for="job_role">job role</label>
                        <select name="job_role" id="jobe_role">
                    <option value="select job role"></option>
                        <option value="front">frontend developer</option>
              <option value="full_stack">full stack</option>
            <option value="ui_ux">UI UX designer</option>                    
            </select>
                    </div>
                    <div class="textarea_control">
                        <label for="address">Address</label>
                        <textarea name="adree" id="id" cols="50" rows="4"
                        placeholder="enter address"></textarea>
                    </div>
                    <div class="form_control">
                    <label for="city">city</label>
                    <input id="city" name="city"
                    placeholder="enter city name..."/>
                    </div>
                   <div class="form_control">
                    <label for="pincode">pincode</label>
                    <input type="number"
                    id="pincode"
                    name="pincode"
                    placeholder="enter pincode name..."/>
                   </div> 
                   <div class="button_container">
                    <button type="submit">APPLY NOW

                    </button>

                   </div>
            
            </form>
                </div>

        </div>
    </div>
</body>
</html>
