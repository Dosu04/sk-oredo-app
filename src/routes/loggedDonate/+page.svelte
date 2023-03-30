<script>
	import Footer from "../../components/Footer.svelte";
import DonateImg from '$lib/images/donate/Image.jpg';
	import NavbarL from "../../components/NavbarL.svelte";

</script>



<main>
  <NavbarL/>
    
  <section class="banner" style="background-color:#AD7BE9;text-align:center; color:white">
    <h1>Campaigns</h1>
  </section>
  <section class="container-fluid main-cont" >
    <div class="searchComp ">
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search Campaigns" aria-label="Search">
        <button class="btn btn-primary searchButt" type="submit">Search </button>
      </form>
    </div>
    <div class="row">
      <div class="col-lg-4">
        <div class="box">
          <div>
            <a href="/donation"><img src={DonateImg} alt="" width="100%"></a>
          </div>
          <div class="content">
            <h4>Food and Clothes for Orphanage Visit</h4>
            <p><strong>N220,000</strong> raised from  <strong>N600,000</strong>   total</p>
            <div class="progress">
              <div class="progress-bar" role="progressbar" style="width: 35%;" aria-valuenow="35" aria-valuemin="0" aria-valuemax="100">35%</div>
            </div> <br><br>
            <div class="row">
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
      <div class="col-lg-4">
        <div class="box">
          <div>
            <a href="/donation"><img src={DonateImg} alt="" width="100%"></a>
          </div>
          <div class="content">
            <h4>Food and Clothes for Orphanage Visit</h4>
            <p><strong>N220,000</strong> raised from  <strong>N600,000</strong>   total</p>
            <div class="progress">
              <div class="progress-bar" role="progressbar" style="width: 15%;" aria-valuenow="15" aria-valuemin="0" aria-valuemax="100">15%</div>
            </div> <br><br>
            <div class="row">
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
      <div class="col-lg-4">
        <div class="box">
          <div>
            <a href="/donation"><img src={DonateImg} alt="" width="100%"></a>
          </div>
          <div class="content">
            <h4>Food and Clothes for Orphanage Visit</h4>
            <p><strong>N220,000</strong> raised from  <strong>N600,000</strong>   total</p>
            <div class="progress">
              <div class="progress-bar" role="progressbar" style="width: 75%;" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">75%</div>
            </div> <br><br>
            <div class="row">
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
    
      </section>
  <Footer/>
</main>

<style>
  
  .donate-butt{

background-color: #AD7BE9;
border-color: #AD7BE9;  }

.donate-butt:hover{
background-color: #9b5fe3;
border-color: #9b5fe3;
}
img{
  
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
}
.box{
  border: solid 0.5px rgb(182, 181, 181) ;
  border-radius: 12px;


}
.content{
    padding: 1rem;
  }
  .progress-bar{
background-color: #AD7BE9;

  }
  .searchButt{

background-color: #AD7BE9;
border-color: #AD7BE9;  }

.searchButt:hover{
background-color: #9b5fe3;
border-color: #9b5fe3;
}
  .col-lg-4{
    margin-bottom: 2rem;
   }
  .searchComp{
    display: grid;
    place-items: center;
    margin-bottom: 5rem;
  }
  form input.me-2{
    width: 100%;
  }
  .banner{
    padding: 3rem 0;
  }
  .main-cont{
    padding: 3rem 3rem;
  }
</style>