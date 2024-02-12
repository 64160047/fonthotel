<script setup lang="ts">
</script>

<template>
    <div class="body overflow-y-auto dc-scroll">
        <!-- The container for the overlay and cards -->
        <a class="btn-booking mt-7 mr-10 inline-block text-center">Book now</a>
        <div class="flex justify-center items-center bigcard">
            <!-- Added classes for centering -->
            <div class="grid relative  card-style  mt-10 text-right">
                <div class="flex grid grid-rows-2  flex-col items-right  ml-10"> <!-- Center alignment -->
                    <div class="flex flex-wrap justify-between items-center  pt-5 font-judson">
                        <p class="text-xl mb-4 text-left">DELUXE ROOM</p>
                    </div>
                    <div class="flex flex-wrap justify-between items-right  pt-2 font-judson">
                        <img class="room-image" :src="imgroom" alt="Room Image">
                        <p class=" text-[13px] mr-10">STAY CLOSE TO TERMINAL 21 AND OTHER SHOPPING MALLS IN BANGKOK CITY</p>
                    </div>

                    <div class=" grid grid-cols-2 gap-2 justify-center flex flex-row-reverse  items-right "> <!-- right alignment -->

                        <div class="flex flex-row-reverse items-right justify-items-end "> <!-- Center alignment -->

                            <div class=" font-judson  ">
                                   
                               
                                    <p class=" text-[13px] text-right mt-6">Spacious Deluxe rooms feature a comfortable
                                    king-size
                                    bed with a
                                    Sealy Posturepedic mattress for a restful night’s sleep, a bathroom with a bathtub,
                                    separate
                                    walk-in rain shower and a bidet toilet. There’s also a seating area and a work desk,
                                    high-speed Wi-Fi, a 49” smart TV, an entertainment centre, and USB port. Amenities
                                    include
                                    coffee and tea making facilities, refrigerator, a safety deposit box, complimentary
                                    daily
                                    newspaper and bottled water. Floor-to-ceiling windows give a fabulous city view while
                                    electric blinds and blackout curtains ensure peaceful sleep whatever your schedule.
                                    Interconnecting rooms are available. </p>
                                

                            </div>
                            
                        </div>

                        <!-- The overlay card with a semi-transparent black background and blur effect -->
                        <div class="flex flex-wrap justify-center items-center gap-5">
                            
                        </div>
                    </div>
                </div>

            </div>



        </div>


    </div>
</template>
  
<style scoped>
.body {
    background-image: url('../images/image.png');
    background-size: cover;
    /* Cover the entire screen */
    background-position: center;
    /* Center the background image */
    background-repeat: no-repeat;
    /* Do not repeat the image */
    width: 100vw;
    height: 100vh;
    /* Make sure the div covers the full height of the viewport */
    position: fixed;
    /* Optional: Fixes the background to the viewport */
    top: 0;
    left: 0;
}

.card-style {
    width: 90vw;
    height: 75vh;
    border-radius: 30px;
    background-color: rgba(229, 229, 229, 0.758);
    /* add filter blue */
    fill-opacity: unset;
    display: block;
}

.bigcard {
    display: flex;
    height: 80vh;
}

.font-judson {
    font-family: 'Judson';
}

.dc-scroll {
    max-height: 100vh;
    overflow: scroll;
}

.dc-scroll::-webkit-scrollbar {
    width: 5px;
    height: 5px;
}

.dc-scroll::-webkit-scrollbar-thumb {
    background-color: #EBBD99;
    border-radius: 10px;
}

.btn-booking {
    background-color: #906843;
    color: white;
    padding: 10px 20px;
    border-radius: 8px;
    box-shadow: 0px 4px 6px #805d3f;
    font-weight: medium;
    text-decoration: none;
    display: inline-block;
    width: 150px;
}</style>
  