<template>
    <v-container fluid>
        <header>
            <nav class="app-bar">
                <div class="navbar-title">British Bytes</div>
                <img src="../../Cracking-the-Coding-Interview-6th-Edition-189-Programming-Questions-and-Solutions.png" alt="Logo" style="height: 60px; margin-right: 8px;" /> 

                <div class="navbar-links">
                    <v-btn >Features</v-btn>
                    <v-btn >Testimonials</v-btn>
                    <v-btn >Link 3</v-btn>
                </div>
                <v-btn class="right-button" style="background-color: darkred; color: white;">Start an Project</v-btn>
            </nav>
        </header>
    </v-container>
</template>

<style>
.app-bar {
    font-size: 20px;
    text-transform: uppercase;
    letter-spacing: 1px;
    display: flex;
    justify-content: space-between; /* Space between title and button */
    align-items: center; /* Center items vertically */
}

.navbar-title {
    flex: 1.5; /* Takes up available space */
    font-weight: bold; /* Bold title for emphasis */
    color: darkred;

}

.navbar-links {
    display: flex;
    justify-content: center; /* Centers the links */
    flex: 8; /* Takes up available space */
    
}


.right-button {
    /* Additional styles for the right button */
    border-radius: 20px; /* Rounded corners */
    padding: 8px 16px; /* Padding for a better button size */
    font-weight: bold; /* Bold text for emphasis */
    text-transform: uppercase; /* Uppercase text */
    letter-spacing: 1px; /* Spacing between letters */
    background-color: darkred;
    color: white; /* White text color */
}
</style>

<!-- 
<template>
    <v-app-bar app  class="px-10" >
      <div class="d-flex align-center">
        <h1 style="color: darkred;">British Bytes </h1>
        <img src="../../Cracking-the-Coding-Interview-6th-Edition-189-Programming-Questions-and-Solutions.png" alt="Logo" style="height: 60px; margin-right: 8px;" /> 

      </div>

      <v-spacer></v-spacer>

 
      <div >
      <v-btn  to="/login">Services</v-btn>
      <v-btn   to="/signup">Testimonials</v-btn>
      <v-btn   to="/signup">FAQ</v-btn>
      <v-btn style="background-color: darkred; color: white; font-weight: bolder;"  to="#">Start a Project</v-btn>

      
      </div>
    


    </v-app-bar>
  </template>  -->