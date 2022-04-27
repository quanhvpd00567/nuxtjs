<!-- Please remove this file from your project -->
<template>
  <div class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0 wsp">
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet">
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8 text-center">
      <div>
        <img style="margin: 0 auto" src="~assets/images/logo.png" alt="" class="w-36">
      </div>
      <div>
        <h3>The BNB Reward Pool with the tastiest daily return and lowest dev fee</h3>
      </div>
      <div class="pt-5 pb-5">
        <a class="btn-connect-now text-white font-bold py-2 px-4 rounded-full border-4" href="aaa">
          Connect Wallet
        </a>
      </div>

      <div>
        <div class="max-w-md card-x rounded-3xl">
          <div class="pt-14 pb-14">
            <table class="w-full ">
              <tbody>
                <tr>
                  <td class="w-4/6 text-left pl-10">Contract</td>
                  <td>0BNB</td>
                </tr>
                <tr>
                  <td class="w-4/6 text-left pl-10">Wallet</td>
                  <td>0BNB</td>
                </tr>
                <tr>
                  <td class="w-4/6 text-left pl-10">Your beef</td>
                  <td>0Beef</td>
                </tr>
              </tbody>
            </table>

            <input class="appearance-none border rounded-lg w-3/5 py-2 px-3 mt-5 text-white mb-3 focus:outline-none focus:shadow-outline text-center"
             type="text" disabled placeholder="0BNB">
            <input class="appearance-none border rounded-lg w-3/5 py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline text-center"
             type="button" disabled value="ROAST BEEF">

             <hr>

             <div class="pt-5 pl-5 pr-5">
               <span class="float-left">Your Reward</span>
               <span class="float-right text-yellow-200 text-2xl">0.00000BNB</span>
             </div>
          </div>
        </div>
      </div>

       <div class="pt-5">
        <a class="btn-connect-now text-white font-bold py-2 px-4 rounded-full border-4">
          Connect Wallet
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>


<style>
.wsp {
  background: url('~assets/images/bg.png');
}

h3{
  color: #E48F0D;
}

.btn-connect-now:hover{
    color: #FFFFFF;
    background-color: #E48F0D;
    border-color: #E48F0D !important;
}
.btn-connect-now{
    font-weight: 700;
    fill: #E48F0D;
    color: #E48F0D;
    background-color: #E48F0D00;
    border-style: solid;
    border-color: #E48F0D !important;
}

.card-x{
  margin: 0 auto !important;
  background: #E48F0D;
}

input{
  border-color: #E48F0D !important;
}
</style>
