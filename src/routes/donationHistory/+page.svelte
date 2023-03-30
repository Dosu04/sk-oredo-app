<script>
	import Footer from "../../components/Footer.svelte";
import Prog from '$lib/images/programs/program.jpg';
import check from '$lib/images/check.png';

	import NavbarL from "../../components/NavbarL.svelte";


</script>

<main>
    <NavbarL/>
    <section style="color:#AD7BE9;text-align:center; ">
        <h1>Donation History</h1>
      </section>
      <section class="container-fluid" style=" padding:3rem 3rem">
        <div class="row">
            <div class="col-lg-4 colz">
              <div class="program">
                <div class="prog-img">
                  <img src={Prog} alt="" width="100%" style="border-top-left-radius: 10px; border-top-right-radius: 10px ;">
                </div>
                <div class="prog-content">
                  <div class="prog-txt">
                    <h4>Food and Clothes for Orphanage Visit</h4>
                    <p><strong>N220,000 </strong>raised from <strong>N600,000</strong> total</p>
                    <div class="progress">
                      <div class="progress-bar" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">35%</div>
                    </div> 
                  </div> 
                           
                  <div class="prog-action row">
                    <div class="col-lg-6">
                      
                    <p style="color:grey; display:inline-block">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
                        <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
                      </svg> 2nd April, 2023 <br>
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                        <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                      </svg> GTX Group
    
                    </p>
                    </div>
                    <div class="action-space col-lg-6" style="text-align:right; " >
                      <a class="btn btn-secondary donate-butt"   href="/donation">Donate</a>
                    </div>
                  </div>
                
                </div>
  
                </div>
            </div><div class="col-lg-4 colz">
              <div class="program">
                <div class="prog-img">
                  <img src={Prog} alt="" width="100%" style="border-top-left-radius: 10px; border-top-right-radius: 10px ;">
                </div>
                <div class="prog-content">
                  <div class="prog-txt">
                    <h4>Food and Clothes for Orphanage Visit</h4>
                    <p><strong>N220,000 </strong>raised from <strong>N600,000</strong> total</p>
                    <div class="progress">
                      <div class="progress-bar" role="progressbar" style="width: 100%;" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100">100%</div>
                    </div> 
                  </div> 
                           
                  <div class="prog-action row">
                    <div class="col-lg-6">
                      
                    <p style="color:grey; display:inline-block">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
                        <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
                      </svg> 2nd April, 2023 <br>
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                        <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                      </svg> GTX Group
    
                    </p>
                    </div>
                    <div class="action-space col-lg-6" style="text-align:right; " >
                      <img src={check} alt="">
                    </div>
                  </div>
                
                </div>
  
                </div>
            </div><div class="col-lg-4 colz">
              <div class="program">
                <div class="prog-img">
                  <img src={Prog} alt="" width="100%" style="border-top-left-radius: 10px; border-top-right-radius: 10px ;">
                </div>
                <div class="prog-content">
                  <div class="prog-txt">
                    <h4>Food and Clothes for Orphanage Visit</h4>
                    <p><strong>N220,000 </strong>raised from <strong>N600,000</strong> total</p>
                    <div class="progress">
                      <div class="progress-bar" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">35%</div>
                    </div> 
                  </div> 
                           
                  <div class="prog-action row">
                    <div class="col-lg-6">
                      
                    <p style="color:grey; display:inline-block">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
                        <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
                      </svg> 2nd April, 2023 <br>
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                        <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                      </svg> GTX Group
    
                    </p>
                    </div>
                    <div class="action-space col-lg-6" style="text-align:right; " >
                      <a class="btn btn-secondary donate-butt"   href="/donation">Donate</a>
                    </div>
                  </div>
                
                </div>
  
                </div>
            </div>
            

          </div>
          <div class="row">
            <div class="col-lg-4 colz">
              <div class="program">
                <div class="prog-img">
                  <img src={Prog} alt="" width="100%" style="border-top-left-radius: 10px; border-top-right-radius: 10px ;">
                </div>
                <div class="prog-content">
                  <div class="prog-txt">
                    <h4>Food and Clothes for Orphanage Visit</h4>
                    <p><strong>N220,000 </strong>raised from <strong>N600,000</strong> total</p>
                    <div class="progress">
                      <div class="progress-bar" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">35%</div>
                    </div> 
                  </div> 
                           
                  <div class="prog-action row">
                    <div class="col-lg-6">
                      
                    <p style="color:grey; display:inline-block">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
                        <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
                      </svg> 2nd April, 2023 <br>
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                        <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                      </svg> GTX Group
    
                    </p>
                    </div>
                    <div class="action-space col-lg-6" style="text-align:right; " >
                      <a class="btn btn-secondary donate-butt"   href="/donation">Donate</a>
                    </div>
                  </div>
                
                </div>
  
                </div>
            </div><div class="col-lg-4 colz">
              <div class="program">
                <div class="prog-img">
                  <img src={Prog} alt="" width="100%" style="border-top-left-radius: 10px; border-top-right-radius: 10px ;">
                </div>
                <div class="prog-content">
                  <div class="prog-txt">
                    <h4>Food and Clothes for Orphanage Visit</h4>
                    <p><strong>N220,000 </strong>raised from <strong>N600,000</strong> total</p>
                    <div class="progress">
                      <div class="progress-bar" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">35%</div>
                    </div> 
                  </div> 
                           
                  <div class="prog-action row">
                    <div class="col-lg-6">
                      
                    <p style="color:grey; display:inline-block">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
                        <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
                      </svg> 2nd April, 2023 <br>
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                        <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                      </svg> GTX Group
    
                    </p>
                    </div>
                    <div class="action-space col-lg-6" style="text-align:right; " >
                      <a class="btn btn-secondary donate-butt"   href="/donation">Donate</a>
                    </div>
                  </div>
                
                </div>
  
                </div>
            </div><div class="col-lg-4 colz">
              <div class="program">
                <div class="prog-img">
                  <img src={Prog} alt="" width="100%" style="border-top-left-radius: 10px; border-top-right-radius: 10px ;">
                </div>
                <div class="prog-content">
                  <div class="prog-txt">
                    <h4>Food and Clothes for Orphanage Visit</h4>
                    <p><strong>N220,000 </strong>raised from <strong>N600,000</strong> total</p>
                    <div class="progress">
                      <div class="progress-bar" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">35%</div>
                    </div> 
                  </div> 
                           
                  <div class="prog-action row">
                    <div class="col-lg-6">
                      
                    <p style="color:grey; display:inline-block">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
                        <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
                      </svg> 2nd April, 2023 <br>
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                        <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                      </svg> GTX Group
    
                    </p>
                    </div>
                    <div class="action-space col-lg-6" style="text-align:right; " >
                      <img src={check} alt="">
                    </div>
                  </div>
                
                </div>
  
                </div>
            </div>
          </div>
      </section>

    
    <Footer/>

</main>

<style>
  .progress-bar{
background-color: #AD7BE9;

  }
  @media(max-width:900px){
    .program{
    padding: 0;
    margin:0;
    border: solid 0.5px rgb(182, 181, 181) ;
    border-radius: 12px;
    width: 15rem;
    }
    
    }


  @media(max-width:300px){
    .program{
    padding: 0;
    margin:0;
    border: solid 0.5px rgb(182, 181, 181) ;
    border-radius: 10px;
    width: 12rem;
    }
    
  }
  .prog-content{
    padding: 0.5rem;
  }
  .program{
    
    border: solid 1px rgb(182, 181, 181) ;
    border-radius: 10px;
  }
  .prog-txt{
    margin-bottom: 5rem;
  }
  .donate-butt{

    background-color: #AD7BE9;
    border-color: #AD7BE9;  }
    
  .donate-butt:hover{
    background-color: #9b5fe3;
    border-color: #9b5fe3;
  }
.colz{
  display: grid;
  place-items:center;
  margin-bottom: 3rem;
}
section{
      padding: 3rem 0;
    }
</style>