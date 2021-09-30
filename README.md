# customer-enquiry-form.html

<head>
  <style type="text/css">
  .star {
color:red;
}
input [type=text], select, area{
width:100%;
paddding:12px;
border: 1px solid #ccc;
margin-top: 6px;
margin-bottom: 16px;
resize: vertical;
}



input[type=Submit ] {
background-color : #5b1e5b;
color: green;
padding: 12px 20px;
border: none;
cursor: pointer;
}



input[type=SEND ENQUIRY]:hover {
background-color: #45a049;
}
.container {
border-radius: 5px;
background-color: 800080;
padding: 20px;
}
  </style>
</head>
<body>
<div class = "container">
  <div style="text-align:left">
  <h1> Customer Enquiry Form</h1>
  <p> Happy Dusherra </p>
  <form action="action_page.php" method="get">
  <span> I want <sup class="star">*</sup></span>
  <select id ="i want " name = "i want">
  <option value=" to enquire about property">To enquire about property</option>
  <option value=" to view this property">To view this property</option>
  </select>
  <br></br>
  <span> Your title <sup class="star">*</sup></span>
  <select id ="your tiltle " name = "your title">
  <option value=" Mr"> Mr </option>
  <option value=" Mrs">Mrs</option>
  </select>
  <br>
  </br>
  <span> Your Name <sup class="star">*</sup></span>
  <input type ="text" id="fname" name ="firstname" placeholder="Your Name..">
  <br></br>
  <span> Your Phone Number <sup class="star">*</sup></span>
  <input type ="text" id="number" name ="number" placeholder="Phone Number">
  <br></br>
  <span> Your Email Address <sup class="star">*</sup></span>
  <input type ="text" id="number" name ="number" placeholder="">
  <br></br>
  <span> I would like to be contacted by <sup class="star"></sup></span>
  <select id ="I would like to be contacted by " name = "I would like to be contacted by">
  <option value=" Phone or Email"> Phone or Email </option>
  <option value=" Email Only">Email Only</option>
  <option value=" Phone Only"> Phone only </option>
  </select>
  <br></br>
  <label for = "i want to be concerned at"> I want to be concerned at</label>
  <select id = "i want to be contacted at" name = "I want to be contacted at ">
  <option value = "anytime">Anytime</option>
  <option value = "Morning">Morning</option>
  <option value = "Evening">Evening</option>
  </select>
  <br></br>
  <span> I live in the following country <sup class="star">*</sup></span>
  <select id = "country" name="country">
  <option value = "Austrailia">Australia</option>
  <option value = "America">America</option>
  <option value = "Germany">Germany</option>
  </select>
  <br></br>
  <span> I have the following questions <sup class="star">*</sup></span>
  <br><br>
  <style>
  .comment{
  resize: none;
  height: 100px;
  width: 350px;
  }
  </style>
  <textarea id="enquiry" name="enquiry" rows="10" cols 50>
  </textarea>
  <br><br>
  <div style="text-align:center">
  <input type="submit" value="SEND ENQUIRY">
  
  
  
  </form>
  
  
  
  <p> Click on the enquiry button for more information about our organization</p></div>
</div>
</body>
