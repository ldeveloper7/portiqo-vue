<template>

    <div>

        <div id="wrapper">
            <!-- start header -->

            <!-- Modal -->
            <div class="modal fade" id="myModal" role="dialog">
                <div class="modal-dialog">

                    <!-- Modal content-->
                    <div class="modal-content">
                        <div class="modal-header">
                            <button type="button" class="close" data-dismiss="modal">&times;</button>
                        </div>
                        <div class="modal-body">
                            <div class="row">
                                <div class="col-md-6 aligncenter">
                                    <img src="img/pop-home.png" width="150">
                                    <h6>Sign Up</h6>
                                    <p class="light-small-text">Create a free Portiqo account<br>to get access to properties.</p>
                                    <p class="signin">Already have an account? <a href="#">SIGN IN</a></p>
                                </div>
                                <div class="col-md-6">
                                    <p class="pop-text">Enter your details</p>
                                    <form name="signup" method="post" action="#" class="aligncenter">
                                        <input type="text" class="form-control input-field light-border" id="fname" placeholder="Full Name">
                                        <input type="text" class="form-control input-field light-border" id="email" placeholder="Email">
                                        <input type="text" class="form-control input-field light-border" id="mobile" placeholder="Mobile Number">
                                        <input type="text" class="form-control input-field light-border" id="address" placeholder="Property Address">
                                        <button type="button" class="btn btn-primary btn-block input-field peach-box">Create Account</button>
                                    </form>
                                </div>
                            </div>
                        </div>
                        <div class="modal-footer">
                        </div>
                    </div>

                </div>
            </div><!-- End Modal -->

            <header>
                <div class="navbar navbar-default fluid">
                    <div class="container">
                        <div class="navbar-header">
                            <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                                <span class="icon-bar"></span>
                                <span class="icon-bar"></span>
                                <span class="icon-bar"></span>
                            </button>
                            <a class="navbar-brand" href="index.html"><img src="img/logo.png" alt="Portiqo" /></a>
                        </div>
                        <div class="navbar-collapse collapse">
                            <ul class="nav navbar-nav" id="responsivemenu">
                                <li><a href="owner.html">owner</a></li>
                                <li><a href="agent.html">agent</a></li>
                                <li><a href="freelance.html">freelance</a></li>
                                <li><a href="referral.html">refer</a></li>
                                <li><a href="#">properties</a></li>
                                <li><a href="#" class="mgnr-15">login</a></li>
                                <li class="cont-btn"><a href="#" class="btn btn-small orange-btn" data-toggle="modal" data-target="#myModal">CONTACT</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </header>
            <!-- end header -->

            <div class="container mgnt-60">
                <p class="onboard_heading">Add Your Property</p>
            </div>

            <div class="container custom_container marb-40">
                <div id="sticky-anchor"></div>
                <div class="row bs-wizard" id="sticky">
                    <div class="col-md-15 bs-wizard-step complete">
                        <div class="progress"><div class="progress-bar"></div></div>
                        <a href="property-type.html" class="bs-wizard-dot"></a>
                        <div class="text-center bs-wizard-stepnum marl-55">Property Type</div>
                    </div>

                    <div class="col-md-15 bs-wizard-step active"><!-- complete -->
                        <div class="progress"><div class="progress-bar"></div></div>
                        <a href="add-photos.html" class="bs-wizard-dot"></a>
                        <div class="text-center bs-wizard-stepnum">Add Photos</div>
                    </div>

                    <div class="col-md-15 bs-wizard-step disabled"><!-- complete -->
                        <div class="progress"><div class="progress-bar"></div></div>
                        <a href="add-projects.html" class="bs-wizard-dot"></a>
                        <div class="text-center bs-wizard-stepnum">Add Project</div>
                    </div>

                    <div class="col-md-15 bs-wizard-step disabled"><!-- complete -->
                        <div class="progress"><div class="progress-bar"></div></div>
                        <a href="property-details.html" class="bs-wizard-dot"></a>
                        <div class="text-center bs-wizard-stepnum">Property Details</div>
                    </div>

                    <div class="col-md-15 bs-wizard-step disabled"><!-- active -->
                        <div class="progress"><div class="progress-bar"></div></div>
                        <a href="listing-details.html" class="bs-wizard-dot"></a>
                        <div class="text-center bs-wizard-stepnum marr-60">Listing Details</div>
                    </div>
                </div>

            </div>

            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <div class="onboard_box onboard_box_hover">
                            <p class="onboard_box_heading-2 text-center">Add Photos</p>
                            <p class="onboard_heading_desc">
                                Beautiful photos grab attention. Add a few photos. You can also and them later.
                            </p>
                            <div class="row mart-50">
                                <ul class="add_photo">
                                    <li><img src="img/add-photo-1.jpg" alt="" /></li>
                                    <li><img src="img/add-photo-2.jpg" alt="" /></li>
                                    <li><img src="img/add-photo-3.jpg" alt="" /></li>
                                    <li><img src="img/add-photo-4.jpg" alt="" /></li>
                                    <li><img src="img/add-photo-5.jpg" alt="" /></li>
                                    <li><img src="img/add-photo-6.jpg" alt="" /></li>
                                    <li><img src="img/add-photo-7.jpg" alt="" /></li>
                                    <li><img src="img/add-photo-8.jpg" alt="" /></li>
                                </ul>
                            </div>
                            <p class="text-center marginbot50">
                                <a href="add-projects.html" class="btn purple_btn">next</a>
                            </p>
                            <p class="text-center marginbot50">
                                <button class="btn purple_btn"><i class="material-icons">cloud_upload</i> upload</button>
                            </p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <div class="onboard_box onboard_box_hover">
                            <p class="onboard_box_heading-2 text-center mart-200">Uploading Photos…</p>
                            <p class="onboard_heading_desc">
                                Your photos are been uploaded and added to your listing.
                            </p>
                            <div class="row mgnt-40  marb-200">
                                <div class="col-md-6 col-md-offset-3">
                                    <div class="progress">
                                        <div class="progress-bar progress_bg" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width:60%">
                                        </div>
                                    </div>
                                    <p class="progress_text">60%</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>



    </div>

</template>