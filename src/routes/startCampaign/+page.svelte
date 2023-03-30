<script>
	import Footer from "../../components/Footer.svelte";
import Navbar from "../../components/Navbar.svelte";

</script>



<main>
  <section style="background-color:#AD7BE9;text-align:center; color:white">
    <h1>Start a Campaign</h1>
  </section>
    <section>
      <form action="">
<div class="container-fluid ">
  <div class="row main-body">
    <div class="col-lg-6">
      <div class="form-check"  style="padding:0 4.5rem;">
        <input class="form-check-input" type="checkbox"  value="" id="customCheck" onclick="changeColor()" />
        <label class="form-check-label" for="customCheck" >
            Call for Volunteers
        </label>
      </div>
      <div class=" inputs" style="padding:0 3rem;">
        <label for="exampleFormControlInput1" class="form-label">Organisation Name</label>
        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Dell International School">
      </div>
      <div class=" inputs" style="padding:0 3rem;">
        <label for="exampleFormControlInput1" class="form-label">Campaing Title</label>
        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="e.g Food and Clothes for Orphanage Visit">
      </div>
      <label for="" style="padding: 0 0 0.5rem 3rem; color:grey">Campaing Category</label><br>
      <div class="btn-group buttGrp1" role="group" aria-label="Basic checkbox toggle button group" style="padding-left:3rem;" >
        <input type="checkbox" class="btn-check" id="btncheck1" autocomplete="off">
        <label class="btn btn-outline-secondary" for="btncheck1">Education</label>
      
        <input type="checkbox" class="btn-check" id="btncheck2" autocomplete="off">
        <label class="btn btn-outline-secondary" for="btncheck2">Food</label>
      

        <input type="checkbox" class="btn-check" id="btncheck3" autocomplete="off">
        <label class="btn btn-outline-secondary" for="btncheck3">HealthCare</label>
      </div><br>
      <div class="btn-group buttGrp2" role="group" aria-label="Basic checkbox toggle button group" style="padding-left:3rem;" >
        <input type="checkbox" class="btn-check" id="btncheck4" autocomplete="off">
        <label class="btn btn-outline-secondary" for="btncheck4">Housing</label>
      </div>
      <br>

      <label for="" style="padding: 0 0 0.5rem 3rem; color:grey">Campaing Amount</label>
      <div class="input-group mb-3 inputs" >

        <span class="input-group-text">₦</span>
        <input type="text" class="form-control" aria-label="Amount (to the nearest naira)">
        <span class="input-group-text">.00</span>
      </div>  
      <div class="form-floating txtAreas">
        <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
        <label  style="padding: 1rem 0 0 4rem; color:grey"for="floatingTextarea2">Campaign Description</label>
      </div>
<div style="padding: 3rem;">
  <label for="date">Campaign Deadline</label>
  <input type="date" id="date" name="date">
 
</div>

<div class="form-group">
  <label style="margin:0 3rem 0.5rem 3rem" for="quantity">Number of Volunteers</label>
  <input style="margin:0 3rem 3rem 3rem; width:11rem" placeholder="e.g. 60" type="number" class="form-control" id="quantity" name="quantity" min="1" max="10" step="1">
</div>
    </div>
    <div class="col-lg-6 lg-screen" style="padding: 0 3rem;">
      <p style="text-align:center">Upload an Image</p>

      <div id="outer-container">
        
        <div id="inner-container">

      <input type="file" id="image" name="image"><br>
        </div>
        
            </div>
      
      </div>
      <div class="col-lg-6 sm-screen" style="width: 80%;" >
        <div>
          <p style="text-align:center">Upload an Image</p>
          <input type="file" id="image" name="image"><br><br><br>
             
        </div>
 

      </div>
    </div>
</div>
        
      
<input type="submit" class="btn btn-primary subCamp" value="Create a Campaign">





</form>
    </section>

<Footer/>
    
</main>

<style>
  @media screen and (max-width: 768px) {
        #outer-container {
          width: 70%;
          margin: 20px auto;
        }
        
        #inner-container {
          border: 1px dashed gray;
        }
        .lg-screen{
          display:none;
        }
      }
      @media screen and (min-width: 768px) {
       
        .sm-screen{
          display:none;
        }
      }
      #outer-container {
        width: 90%;
        max-width: 500px;
        height: 300px;
        margin: 50px auto;
        background-color: #fff;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
      }
      #inner-container {
        width: 80%;
        height: 80%;
        border: 2px dashed gray;
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
      }
  .main-body{padding:0;}
  .subCamp{
    margin: 0 3rem;
    width: 18rem;
    background-color: #AD7BE9;
    border-color: #AD7BE9;
  }
  .subCamp:hover{
    margin: 0 3rem;
    width: 18rem;
    background-color: #9C5EBF;
    border-color: #9C5EBF;
  }

  label[for="date"] {
  color: grey;
  display: block;
  margin-bottom: 5px;
}

input[type="date"] {
  background-color: #F5F5F5;
  padding: 5px;
  border-radius: 5px;
}

input[type="date"]:hover,
input[type="date"]:focus {
  outline: none;
  border-color: #9C5EBF;
  box-shadow: 0 0 5px rgba(173, 123, 233, 0.5);
}
 
  .txtAreas{
    margin-top: 3rem;
    padding: 0 3rem;
    width: 22rem;
  }
  .buttGrp1{
    
    margin-bottom: 1rem;
  }
  .buttGrp2{
    
    margin-bottom: 3rem;
  }

  .btn-outline-secondary{
        margin-right: 1rem;
    }
  .btn-check:checked + .btn-outline-secondary {
    background-color: #AD7BE9;
    border-color: #AD7BE9;
  }

    .btn-check:checked + .btn-outline-secondary {
    background-color: #AD7BE9;
    border-color: #AD7BE9;
  }
    .inputs{
        width: 20rem;
        margin-bottom: 3rem;
        padding:0 3rem;
    }
    .inputs label{
        color: grey
    }
    section{
      padding: 3rem 0;
    }
    .form-check{
        margin-bottom: 3rem;
    }
    .form-check-input:checked {
    background-color: #AD7BE9 !important;
    border-color: #AD7BE9 !important;
  }
</style>