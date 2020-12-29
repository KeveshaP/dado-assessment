<template>
  <div>
    <!--Navbar-->
    <div class="nav-menu-bar">
    <mdb-navbar light color="light"  name="Your Logo" href="#">
      <mdb-navbar-toggler >
        <mdb-navbar-nav>
          <div class="header font">
            <mdb-nav-item class="header-logo"> <img src="//cdn.shopify.com/s/files/1/0015/4874/6807/t/109/assets/logo-homepage-blue.svg?v=6718153341871157066" class="primary_logo" alt="Petlab Co."></mdb-nav-item>
            
              <mdb-nav-item>
                <div @mouseover="mouseOver">Version 1 
                <i v-show="!active" class="fas fa-angle-down"></i>
                <i v-show="active" class="fas fa-angle-up"></i>
                </div>   
              </mdb-nav-item>
                 <br/>
                 <div v-show="active" class="nav-menu-nested">
                <mdb-dropdown-menu>
                  <mdb-dropdown-item>Action</mdb-dropdown-item>
                  <mdb-dropdown-item>Another action</mdb-dropdown-item>
                  <mdb-dropdown-item>Something else here</mdb-dropdown-item>
                </mdb-dropdown-menu>
                </div>
                &nbsp;&nbsp;
             <mdb-nav-item>
                <div @mouseover="mouseOver2">Version 2
                <i v-show="!active2" class="fas fa-angle-down"></i>
                <i v-show="active2" class="fas fa-angle-up"></i>
                </div>   
              </mdb-nav-item>
                 <br/>
                 <div v-show="active2" class="nav-menu-nested">
                <mdb-dropdown-menu>
                  <mdb-dropdown-item>Action</mdb-dropdown-item>
                  <mdb-dropdown-item>Another action</mdb-dropdown-item>
                  <mdb-dropdown-item>Something else here</mdb-dropdown-item>
                </mdb-dropdown-menu>
                </div>
              
          </div>
        </mdb-navbar-nav>
        <!-- Search form -->
      </mdb-navbar-toggler>

    </mdb-navbar>

    </div>
    <!--/.Navbar-->
    <div class="nav-bar-view-height">
        <div  class="first-bn-block-bg-main">
        <div class="centered text-left">
          <h1  class="display-1">WELCOME</h1>
          <h1  class="display-4">
            We’re Petlab Co. A company built <br/>for pet owners, by pet owners.</h1>
            <p>
              We provide everything from vitamin supplements to grooming products, <br/> all aimed at supporting our pets to help them live a longer, healthier and happier life
            </p>
        </div>
      </div>
    </div>
    <div class="p-5 m-5">
      <mdb-row>
        <mdb-col xl="12" md="12" class="m-5 text-center">
      <h1 ><b>Meet The Pets Of Petlab</b></h1>
        </mdb-col>
      </mdb-row>
	<mdb-container>
		<mdb-row>
			<mdb-card-group deck>
				<mdb-card class="p-3">
						<a href="#!" >
            <img src="https://mdbootstrap.com/img/Photos/Avatars/img(31).jpg" class="img-fluid z-depth-1 rounded-circle"
                alt="Responsive image">
						</a>
					<mdb-card-body>
					<br/>
          <h5>Zeeko</h5>
          CTO (Chief Tasting Officer)<br/>
          <mdb-btn color="danger" class="read-more-button" @click.native="showModal7 = true"><u>Read More About me </u></mdb-btn>
          <mdb-modal fullHeight position="right" direction="right" :show="showModal7" @close="showModal7 = false">
            <mdb-modal-header>
              <mdb-modal-title>Modal title</mdb-modal-title>
            </mdb-modal-header>
            <mdb-modal-body>...</mdb-modal-body>
            <mdb-modal-footer>
              <mdb-btn color="secondary" @click.native="showModal7 = false">Close</mdb-btn>
              <mdb-btn color="primary">Save changes</mdb-btn>
            </mdb-modal-footer>
          </mdb-modal>
					</mdb-card-body>
				</mdb-card>
        <mdb-card class="p-3">
						<a href="#!" >
            <img src="https://mdbootstrap.com/img/Photos/Avatars/img(31).jpg" class="img-fluid z-depth-1 rounded-circle"
                alt="Responsive image">
						</a>
					<mdb-card-body>
					<br/>
          <h5>Zeeko</h5>
          CTO (Chief Tasting Officer)<br/>
          <mdb-btn color="danger" class="read-more-button" @click.native="showModal7 = true"><u>Read More About me </u></mdb-btn>
          <mdb-modal fullHeight position="right" direction="right" :show="showModal7" @close="showModal7 = false">
            <mdb-modal-header>
              <mdb-modal-title>Modal title</mdb-modal-title>
            </mdb-modal-header>
            <mdb-modal-body>...</mdb-modal-body>
            <mdb-modal-footer>
              <mdb-btn color="secondary" @click.native="showModal7 = false">Close</mdb-btn>
              <mdb-btn color="primary">Save changes</mdb-btn>
            </mdb-modal-footer>
          </mdb-modal>
					</mdb-card-body>
				</mdb-card>
        <mdb-card class="p-3">
						<a href="#!" >
            <img src="https://mdbootstrap.com/img/Photos/Avatars/img(31).jpg" class="img-fluid z-depth-1 rounded-circle"
                alt="Responsive image">
						</a>
					<mdb-card-body>
					<br/>
          <h5>Zeeko</h5>
          CTO (Chief Tasting Officer)<br/>
          <mdb-btn color="danger" class="read-more-button" @click.native="showModal7 = true"><u>Read More About me </u></mdb-btn>
          <mdb-modal fullHeight position="right" direction="right" :show="showModal7" @close="showModal7 = false">
            <mdb-modal-header>
              <mdb-modal-title>Modal title</mdb-modal-title>
            </mdb-modal-header>
            <mdb-modal-body>...</mdb-modal-body>
            <mdb-modal-footer>
              <mdb-btn color="secondary" @click.native="showModal7 = false">Close</mdb-btn>
              <mdb-btn color="primary">Save changes</mdb-btn>
            </mdb-modal-footer>
          </mdb-modal>
					</mdb-card-body>
				</mdb-card>
        <mdb-card class="p-3">
						<a href="#!" >
            <img src="https://mdbootstrap.com/img/Photos/Avatars/img(31).jpg" class="img-fluid z-depth-1 rounded-circle"
                alt="Responsive image">
						</a>
					<mdb-card-body>
					<br/>
          <h5>Zeeko</h5>
          CTO (Chief Tasting Officer)<br/>
          <mdb-btn color="danger" class="read-more-button" @click.native="showModal7 = true"><u>Read More About me </u></mdb-btn>
          <mdb-modal fullHeight position="right" direction="right" :show="showModal7" @close="showModal7 = false">
            <mdb-modal-header>
              <mdb-modal-title>Modal title</mdb-modal-title>
            </mdb-modal-header>
            <mdb-modal-body>...</mdb-modal-body>
            <mdb-modal-footer>
              <mdb-btn color="secondary" @click.native="showModal7 = false">Close</mdb-btn>
              <mdb-btn color="primary">Save changes</mdb-btn>
            </mdb-modal-footer>
          </mdb-modal>
					</mdb-card-body>
				</mdb-card>
			</mdb-card-group>
		</mdb-row>
	</mdb-container>
    </div>
     
  </div>
  
</template>

<script>
import { mdbNavbar, mdbNavItem, mdbNavbarNav, mdbNavbarToggler,  mdbDropdownItem, mdbDropdownMenu,
  mdbContainer, mdbRow, mdbCol, mdbCard,  
  mdbCardBody, mdbCardGroup ,mdbBtn, mdbModal, mdbModalHeader, mdbModalTitle, mdbModalBody, mdbModalFooter } from 'mdbvue';

export default {
   data() {
     return {
      active:false,
      active2:false,
      showModal7: false,
      mailAddress: '@mdo'
    };
  },
    name: 'NavigationPage',
  components: {
      mdbBtn,
      mdbModal,
      mdbModalHeader,
      mdbModalTitle,
      mdbModalBody,
      mdbModalFooter,
      mdbNavbar,
      mdbNavItem,
      mdbNavbarNav,
      mdbNavbarToggler,
      // mdbDropdown,
      mdbDropdownItem,
      mdbDropdownMenu,
      // mdbDropdownToggle,
      mdbContainer,
      mdbRow,
			mdbCol,
			mdbCard,
			mdbCardBody,
			mdbCardGroup,
  },
   methods: {
        mouseOver: function(){
          this.active2 =  false;
            this.active = !this.active;   
        },
         mouseOver2: function(){
          this.active1 =  false;

            this.active2 = !this.active2;   
        }
    },
  mounted() {
    document.getElementById("main-navbar").style.height = '60px';
  },
  beforeDestroy() {
    document.getElementById("main-navbar").style.height = null;
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.view {
  background: url("https://mdbootstrap.com/img/Photos/Others/img (43).jpg")no-repeat center center;
  background-size: cover;
  height: 100%;
}
mdb-card{
background-color: transparent;
}
.card{
  position: relative;
    display: -ms-flexbox;
    display: -webkit-box;
    display: flex;
    -ms-flex-direction: column;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    flex-direction: column;
    min-width: 0;
    word-wrap: break-word;
    background-color: transparent;
    /* background-clip: border-box; */
    border: 0px solid rgba(0,0,0,.125);
    /* border-radius: .25rem;*/
    font-weight: 400;
    border: 0;
    /* -webkit-box-shadow: 0 2px 5px 0 rgba(0,0,0,0.16), 0 2px 10px 0 rgba(0,0,0,0.12); */
    box-shadow: 0 0 0 0 rgba(0,0,0,0.16), 0 0 0 0 rgba(0,0,0,0.12);
}
.card:hover{
 border-radius: 20px;
 background-color: #fff;
}
.read-more-button{
  color: red;
  background-color: transparent !important;
     box-shadow: 0 0 0 0 rgba(0,0,0,0.16), 0 0 0 0 rgba(0,0,0,0.12);
  display: inline-block;
  padding: 6px 12px;
  margin-bottom: 0;
  font-size: 14px;
  font-weight: normal;
  line-height: 1.42857143;
  text-align: center;
  white-space: nowrap;
  vertical-align: middle;
  cursor: pointer;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 4px;
}
.header-transparent{
  background-color: transparent !important;
  height:0px;display: flex; align-items: center; justify-content:center;

}
.dropdown-menu {
    top: 100px !important;
    left: -100px !important;
    position: relative!important;
}
.font {
    font-family: 'P22-Book', sans-serif;
    font-style: normal;
    font-size: 20px;
    line-height: 0;
}
.centered {
  position: absolute;
  top: 30%;
  left: 30%;
  transform: translate(-50%, -50%);
}
.nav-bar-view-height{
  height: 50vh; margin-bottom: -25px;
}
.header-logo{
  width:250px; text-align:left;
}
.nav-menu-nested{
  height: 100px; width: 0px;
}
.nav-menu-bar{
  background-color:white; width:100%;
}
</style>
