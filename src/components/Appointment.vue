<template>
   <section class="px-5 mt-5">
      <div class="flex justify-between items-center">
         <span class="text-blue-500 text-sm font-medium">
            My Appointment
         </span>
         <span class="text-gray-400 text-xs font-medium">
            Today
         </span>
      </div>
      
      <div class="mt-3 bg-primary p-3 rounded-lg">
         <div class="flex justify-between">
            <div class="flex gap-2">
               <img src="/profile.jpg" class="rounded-lg" width="60" />
               <div class="text-gray-100">
                  <strong class="text-xs">Dr. Amanda Kirana</strong>
                  <p class="text-xxs">Psychologist</p>
               </div>
            </div>
            <div>
               <span class="bg-green-400 px-2 py-1 rounded-lg grid place-items-center">
                  <i class="text-gray-50 text-sm fas fa-phone-alt"></i>
               </span>
            </div>
         </div>
         <div class="bg-blue-300 mt-3 flex justify-between items-center text-gray-300 rounded-lg bg-opacity-50 py-1 px-3">
            <span class="text-xxs gap-2">
               <i class="text-xxs fa fa-clock"></i>
               <small>
                  12:00 PM
               </small>
            </span>
            <span class="text-xxs">
               <i class="text-xxs mr-1 fas fa-calendar-alt"></i>
               <small>Friday, 29 September 2021</small>
            </span>
         </div>
      </div>
      
   </section>
</template>