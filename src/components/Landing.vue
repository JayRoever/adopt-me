<template>
    <div>
        <div class='header'>
            <b-container>
                <b-row>
                    <b-col>
                        <b-navbar toggleable='lg' type='dark' variant="red">
                            <b-navbar-brand to='/'><img src="../assets/logo.png">Adoptme.Org</b-navbar-brand>
                            <b-navbar-toggle target='nav-collapse'></b-navbar-toggle>
                            <b-collapse is-nav id='nav-collapse'>
                                <b-navbar-nav class="ml-auto">
                                    <b-nav-item to='/'><h2>WHAT we do</h2></b-nav-item>
                                    <b-nav-item to='/'><h2>WHO we are</h2></b-nav-item>
                                    <b-nav-item to='/'><h2>EVENTS adoption</h2></b-nav-item>
                                </b-navbar-nav>
                            </b-collapse>
                        </b-navbar>
                    </b-col>
                </b-row>
            </b-container>
        </div>
        
        <div class='trim-img'>
            <b-img center src='../assets/dogs.jpg' fluid alt='Puppies' class='landing-img'></b-img>
            <div class='shadow-bar'>
                <b-container>
                    <b-row>
                        <b-col>
                            <div> <h1>This is your new family!</h1> 
                                <div class='adopt-btn sqr-btn white-btn'>ADOPT NOW</div>
                            </div>
                        </b-col>
                    </b-row>
                </b-container>
            </div>
        </div>

        <b-container fluid="sm">

            <b-row >
                <b-col lg='4' class='pad-top justify-content-flex-start align-items-stretch d-flex'>
                    <b-card no-body class='card-shadow'>
                        <b-card-header header-bg-variant='blue' header-text-variant='white' class="rounded-0">
                            <h2>VOLUNTEERS</h2>
                        </b-card-header>
                        <b-card-img src='../assets/girl.png' class="rounded-0"></b-card-img>
                        <b-card-body class='volunteer-card'>
                            <b-container>

                                <b-row no-gutters>
                                    <b-col sm='8'>
                                        Amazing people, doing the difference every single day. Join us now and be part of a community that is changing the world.
                                    </b-col>
                                </b-row>

                                <b-row no-gutters>
                                    <b-col sm='8'>
                                        <div class='join-btn sqr-btn blue-btn'>JOIN US</div>
                                    </b-col>
                                </b-row>

                            </b-container>
                        </b-card-body>
                    </b-card>
                </b-col>

                <b-col lg='8' class='pad-top'>
                     <b-card no-body>
                        <b-card-header header-bg-variant='red' header-text-variant='white' class="rounded-0">
                            <h2>TESTIMONIAL OF THE MONTH</h2>
                        </b-card-header>
                        <div>
                            <b-card-img src='../assets/testimonial.jpg' class="rounded-0"></b-card-img>
                            <b-card-body class='overlay'>
                                Mangi, my best friend who saved my life
                            </b-card-body>
                        </div>
                    </b-card>
                </b-col>
            </b-row>

            <b-row>
                <b-col lg='6' class='pad-top'>
                   <b-tabs>
                        <b-tab title="PROGRAMS " active>

                            <b-card no-body class="pad-top" style="max-width: 100%" text-variant='gray'>
                                <b-row no-gutters>
                                <b-col md="4" align-self="center">
                                    <b-card-img src="../assets/friend-in-trouble.png" alt="Dog in doghouse" class="rounded-0"></b-card-img>
                                </b-col>
                                <b-col md="8">
                                    <b-card-body title="BEHAVIOR PROGRAM" title-tag='programs-title'>
                                    <b-card-text>
                                        Evaluation of each dog using specialists who determine the best training that will help your friend be a better family member
                                        <div class='read-more-btn sqr-btn red-btn'>READ MORE</div>
                                    </b-card-text>
                                    </b-card-body>
                                </b-col>
                                </b-row>
                            </b-card>

                            <b-card no-body class=" pad-top" style="max-width: 100%;" text-variant='gray'>
                                <b-row no-gutters>
                                <b-col md="4" align-self="center">
                                    <b-card-img src="../assets/next-family.jpg" alt="Two friendly dogs" class="rounded-0"></b-card-img>
                                </b-col>
                                <b-col md="8">
                                    <b-card-body title="MY NEXT FAMILY" title-tag='programs-title'>
                                    <b-card-text>
                                        Are you looking for a new family memeber? Then, this program is for you. Dont buy, adopt here, and let's gove a home to these amazing friends
                                        <div class='read-more-btn sqr-btn red-btn'>READ MORE</div>
                                    </b-card-text>
                                    </b-card-body>
                                </b-col>
                                </b-row>
                            </b-card>

                        </b-tab>
                        <b-tab title="ASSOCIATED COMPANIES ">
                            COMPANIES HERE
                        </b-tab>
                    </b-tabs>
                </b-col>

                <b-col lg='6'>
                    <b-img src="../assets/adopt-me.jpg" fluid class='pad-top'></b-img>
                </b-col>
            </b-row>
        </b-container>

        <div class='footer'>
            <b-container>
                    <b-row>
                        <b-col>
                            <b-navbar toggleable='md' type='dark' variant="blue">
                                <b-navbar-brand to='/'><img src="../assets/logo.png">Adoptme.Org</b-navbar-brand>
                                <b-navbar-nav class="ml-auto">
                                    <b-nav-item to='/'>WHAT we do</b-nav-item>
                                    <b-nav-item to='/'>WHO we are</b-nav-item>
                                    <b-nav-item to='/'>EVENTS adoption</b-nav-item>
                                </b-navbar-nav>
                            </b-navbar>
                        </b-col>
                    </b-row>

                    <b-row>
                        <b-col class='address'>
                            Main Street #12345 <br>
                            Awesome City, 45677
                        </b-col>
                    </b-row>
            </b-container>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Landing',
}
</script>

<style lang="scss">
</style>