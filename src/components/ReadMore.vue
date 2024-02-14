<script setup lang="ts">
</script>

<template>
    <div class="body overflow-y-auto dc-scroll">
        <!-- The container for the overlay and cards -->
        <a class="btn-booking mt-7 mr-10 inline-block text-center">Book now</a>
        <div class="flex justify-center items-center bigcard">
            <!-- Added classes for centering -->
            <div class="grid relative  card-style  mt-10 ">
                <div class="flex grid grid-rows-1 grid-cols-2  flex-col items-right  ml-10 "> <!-- Center alignment -->
                    <div class="flex flex-wrap justify-between items-center  pt-5  font-judson">
                        <p class="text-xl mb-4 text-left">DELUXE ROOM</p>
                        <div class="flex grid-cols-2 justify-between items-center  font-judson">

                        </div>
                    </div>

                    <div class="flex grid-cols-2 justify-between items-center mt-10 pt-5  font-judson">
                        <p class="text-sm  text-gray-900 dark:text-white mb-4 text-left">STAY CLOSE TO TERMINAL 21 AND OTHER
                            HOPPING MALLS IN BANGKOK CITY</p>

                    </div>
                    <div class="flex flex-wrap justify-between items-center  pt-5  font-judson">

                    </div>
                    <div class="flex grid-cols-2 justify-between items-center pt-3  font-judson">
                        <p class="text-sm  text-gray-900 dark:text-white mb-4 text-left">Spacious Deluxe rooms feature a
                            comfortable king-size bed with a Sealy Posturepedic mattress for a restful night’s sleep, a
                            bathroom with a bathtub, separate walk-in rain shower and a bidet toilet. There’s also a seating
                            area and a work desk, high-speed Wi-Fi, a 49” smart TV, an entertainment centre, and USB port.
                            Amenities include coffee and tea making facilities, refrigerator, a safety deposit box,
                            complimentary daily newspaper and bottled water. Floor-to-ceiling windows give a fabulous city
                            view while electric blinds and blackout curtains ensure peaceful sleep whatever your schedule.
                            Interconnecting rooms are available.</p>
                    </div>


                </div>

                <div class="flex grid grid-rows-1  flex-col items-right  ml-10 "> <!-- Center alignment -->
                    <div class="flex flex-wrap justify-between items-center  pt-5  font-judson">
                        <p class="text-sm mb-4 text-left">FACILITIES</p>
                    </div>

                </div>
                <div class="flex grid gap-10 grid-rows-3  grid-cols-3 flex-col items-center  ml-10 ">
                    <!-- Center alignment -->
                    <div class="text-center font-judson">
                        <img class="rounded-lg size-9  " src="../images/bed.png" alt="">
                        <p class="text-sm mb-4 md-5 pa-10 ">1.8 m king size bed</p>
                    </div>
                    <div class="text-center font-judson">
                        <p class="text-sm mb-4 ">Chrome cast & Apple mirror apps</p>
                    </div>
                    <div class="text-center font-judson">
                        <p class="text-sm mb-4 ">Electric curtain and sheer</p>
                    </div>
                    <div class="text-center font-judson">
                        <p class="text-sm mb-4 ">Separate Bath & Shower</p>
                    </div>
                    <div class="text-center font-judson">
                        <p class="text-sm mb-4 ">Complimentary High Speed WiFi</p>
                    </div>
                    <div class="text-center font-judson">
                        <p class="text-sm mb-4 ">Complimentary Water</p>
                    </div>
                    <div class="text-center font-judson">
                        <p class="text-sm mb-4 ">Working desk</p>
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
}
</style>
  