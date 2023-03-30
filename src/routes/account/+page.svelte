<script>
import Usr from '$lib/images/nav/user.png';


</script>


<style>
img{
    border-radius: 100%;
}
main{
    text-align: center;
}
.sett-body{

    display: grid;
    place-items: center;
    padding-bottom: 5rem;
}
h1{
    color: #AD7BE9;

}
.title{
    margin-bottom: 5rem;
    margin-top: 5rem;
}
.submit-butt{

background-color: #AD7BE9;
border-color: #AD7BE9;  }

.submit-butt:hover{
background-color: #9b5fe3;
border-color: #9b5fe3;
}
</style>

<main class="container-fluid" style="height: 100vh;">
    
    <div class="sett-body">
        <span class="title">
            <h1>Account Settings</h1>
            <p>Edit your information</p>
        </span>
        <div class="accordion accordion-flush" id="accordionFlushExample">
            <div class="accordion-item">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                  Basic Information
                </button>
              </h2>
              <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <div class="accordion-body">
                    <form action="">
                        <div class="mb-3">
                            <div class="profile-pic">
                                <!-- svelte-ignore a11y-img-redundant-alt -->
                                <img src={Usr} alt="profile picture" id="profile-img" width="200rem"><br>
            
            <div class="profile-upload ">
<br>
              <label style="color: #0083d3;" for="img">Upload Profile Picture</label>
<input id="img" name="profile_photo" placeholder="Photo"  type="file" accept="image/*" onchange="loadFile(event)" style="display:none;">

<script>
    var loadFile = function(event) {
        var image = document.getElementById('profile-img');
        image.src=URL.createObjectURL(event.target.files[0]);
    };

    $('input[type=file]').change(function(){
if($('input[type=file]').val()==''){
document.querySelector('#updatebtn').disabled = true;
} 
else{
document.querySelector('#updatebtn').disabled = false;
}
});

</script> 
 

            </div>
          </div>
                       </div>
                        
                        <div class="mb-3">
                            <label for="exampleFormControlInput1" class="form-label">Full Name</label>
                            <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="e.g. Emmanuel Oladosu">
                          </div>
                          <div class="mb-3">
                            <label for="exampleFormControlInput1" class="form-label">Email Address</label>
                            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="e.g. name@example.com">
                          </div>
                          <br>
                          <input class="btn btn-primary submit-butt" type="Submit" value="Save Changes"/>
                    </form>
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                    Password Security 
                </button>
              </h2>
              <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <div class="accordion-body">
                    <form action="">
                        <div class="mb-3">
                            <label for="exampleFormControlInput1" class="form-label">Old Password</label>
                            <input type="password" class="form-control" id="exampleFormControlInput1" placeholder="Password">
                          </div>
                          <div class="mb-3">
                            <label for="exampleFormControlInput1" class="form-label">New Password</label>
                            <input type="password" class="form-control" id="exampleFormControlInput1" placeholder="Password">
                          </div>
                          <div class="mb-3">
                            <label for="exampleFormControlInput1" class="form-label">Confirm Password</label>
                            <input type="password" class="form-control" id="exampleFormControlInput1" placeholder="Password">
                          </div>

                          <input class="btn btn-primary submit-butt" type="Submit" value="Save Changes"/>
                            
                    </form>
                </div>
              </div>
            </div>
           
          </div>
    </div>
</main>
