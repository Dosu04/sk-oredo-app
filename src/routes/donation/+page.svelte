<script>
  import DonateImg2 from '$lib/images/donate/Image2.jpg';
  import PS from '$lib/images/donate/paystack.png';
  import MAP from '$lib/images/donate/MAP.jpg';	
  import Footer from "../../components/Footer.svelte";
  


</script>


<main>

<div class="container-fluid" style="">
    <div class="row"style="">
        <div class="col-lg-6"style="">
<div>
    <div >
        <img src={DonateImg2} alt="" width="100%" style="border-radius-top-left:15px; border-radius-top-right:15px">
    </div> <br>
    <div class="content-txt">
        <h4>Food and Clothes for Orphanage Visit</h4> <br>
        <p>Dell International Schools has expressed its desire to visit an orphanage and donate food and clothes to the children there. The school aims to make a positive impact on the lives of these children by providing them with basic necessities and showing them that they are cared for and valued. The school administration is working with the students to organize a donation drive for non-perishable food items and gently used clothes, which will be distributed during the visit.</p>
        <p><strong>N220,000</strong>raised from  <strong>N600,000</strong>   total</p>
        
        <div class="progress">
          <div class="progress-bar" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">35%</div>
        </div>
        <br>
        <p style="color:grey; display:inline-block; margin-right:2rem">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
              <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
            </svg> 2nd April, 2023
        </p>
        <p style="color:grey; display:inline-block;">

            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
              <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
            </svg> Dell International School

          </p>
    </div>
</div>
        </div>
        
        <div class="col-lg-6"style="">
            <form action="">
                
                <div class="acc">
                    <div class="accordion accordion-flush" id="accordionFlushExample">
                        <div class="accordion-item">
                          <h2 class="accordion-header" id="flush-headingOne">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                                Make Donation                            </button>
                          </h2>
                          <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">
                                <div class="row">
                                  <strong>*Bank Transfer</strong><br><br>

                                  <div class="col-lg-4">
                                    <p>DELL INTERNATIONAL SCHOOLS</p>
                                    <strong>Account Name</strong>                                    
                                  </div>
                                  <div class="col-lg-4">
                                    <p>2190438943</p>
                                    <strong>Account Number</strong>                                    
                                  </div>
                                  <div class="col-lg-4">
                                    <p>UNITED BANK OF AFRICA (UBA)</p>
                                    <strong>Bank Name</strong>                                    
                                  </div>
                                </div><hr> <br>


                                <div class="row">
                                  <strong>*Card Payment</strong><br><br>
                                  <p>Choose a payment method</p>
                                  <a href=""><img src={PS} alt="" style="width:40%"></a>
                                  
                                <div style="margin-top: 1rem;">
                                  <a href="" class="btn btn-primary butt">Make Payment</a>                            

                                </div>


                                </div>
                            </div>
                          </div>
                        </div>
                        <div class="accordion-item">
                          <h2 class="accordion-header" id="flush-headingTwo">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                                Deliver Donation                          </button>
                          </h2>
                          <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">
                              <strong>*Delivery Address</strong><br><br>
                              <p>DELL INTERNATIONAL SCHOOLS, 7-10 ELUUU P, GRV, LAGOS STATE.</p>
                              <img src={MAP} alt="" style="width:90%"> <br><br>
                              <a href="" class="btn btn-primary butt">Open in Maps</a>                            
                            </div>
                          </div>
                        </div>
                        
                      </div>
                
                      <br><br>
                    
                      <input type="submit" class="btn btn-primary butt" value="Submit">
                </div>

            </form>
        </div>
    </div>

</div>
<Footer/>
</main>


<style>
@media(max-width:750px){
    .container-fluid{
    padding: 5rem 1rem 0rem 1rem;
}
    
  }

@media(min-width:750px){
    .container-fluid{
    padding: 5rem 3rem 0rem 3rem;
}
    
  }
  .progress-bar{
background-color: #AD7BE9;

  }
 
 .butt{

background-color: #AD7BE9;
border-color: #AD7BE9;  }

.butt:hover{
background-color: #9b5fe3;
border-color: #9b5fe3;
}
.acc{
    padding: 1rem;
    border-radius: 10px;
}

.col-lg-6{
 margin-bottom: 3rem;
}
</style>