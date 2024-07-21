<script>
	import newlogo from '$lib/imagesprop/newlogo.png'
	import icons8 from '$lib/imagesprop/icons8.png'
	import icons8_menu from '$lib/imagesprop/icons8_menu.png'
	import smartmockups from '$lib/imagesprop/smartmockups.png'
	import icons8_phone from '$lib/imagesprop/icons8_phone.png'
    import icons8_phone_2 from '$lib/imagesprop/icons8_phone_2.png'
	import icons8_phone_256 from '$lib/imagesprop/icons8_phone_256.png' 
	import icons8_call from '$lib/imagesprop/icons8_call.png' 	
</script>

<div class="all">
<div class="component">
  <div class="w-[390px] h-[152px] p-5 bg-white rounded-bl-3xl rounded-br-3xl justify-between items-end inline-flex">
	<img alt="The project logo" src={newlogo} />
	<div class="w-[70px] h-[70px] relative"></div>
		<div class="h-[73px] justify-end items-center flex">
	  <div class="text-center text-sky-950 text-xl font-semibold font-['K2D'] leading-[31px] tracking-wide">1.000.000.000</div>
	  <div class="justify-start items-center gap-2.5 flex">		
		<img class="w-8 h-8" src={icons8}/>
		<div class="w-8 h-8 relative">
		  <img class="w-8 h-8 left-0 top-0 absolute" src={icons8_menu}/>
		</div>
	  </div>
	</div>
  </div>
</div>
  <div class="componentExternal">
  <div class="w-[360px] h-[297px] relative">
	<div class="w-[180px] h-[0px] left-0 top-[207px] absolute origin-top-left -rotate-90 border-4 border-sky-950"></div>
	<div class="w-[350px] h-[297px] left-[10px] top-0 absolute">
	  <div class="w-[350px] h-[235px] left-0 top-0 absolute text-sky-950 text-[45px] font-semibold font-['Mada'] leading-[52px]">Connecting Businesses, Innovating Communications</div>
	  <div class="w-[350px] left-0 top-[237px] absolute text-stone-950/opacity-60 text-base font-normal font-['Khula'] leading-tight">Provides a brief overview of the company's specialization in providing VoIP services to small and medium-sized businesses.</div>
	</div>
  </div>
  <img class="w-[360px] h-[297px] relative" src={smartmockups} />  
</div>

<div class="component">
  <div class="w-[390px] h-[412px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[60px] inline-flex">
	<div class="w-[348px] h-[101px] relative">
	  <div class="w-[348px] h-[100px] left-0 top-0 absolute text-center text-sky-950 text-4xl font-semibold font-['Mada'] leading-10">Everything you can do with Towitlinks</div>
	</div>
	<div class="w-[350px] h-[211px] relative">
	  <img class="w-[50px] h-[50px] left-[150px] top-0 absolute" src={icons8_phone} />
	  <div class="w-[350px] h-[131px] left-0 top-[80px] absolute flex-col justify-start items-center inline-flex">
		<div class="self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px]">VoIP Calls</div>
		<div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Make and receive calls from anywhere, anytime, with crystal-clear quality and cost-effective pricing.</div>
	  </div>
	</div>
  </div>
</div>
<div class="component">
  <div class="w-[390px] h-[292px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[30px] inline-flex">
	<img class="w-[60px] h-[60px]" src={icons8_phone_2} />
	<div class="w-[350px] h-[131px] left-0 flex-col justify-start items-center flex inline-flex">
	  <div class="self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px]">Text & Fax</div>
	  <div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Stay connected with colleagues, partners, and clients through integrated text and fax services, eliminating the need for separate devices.</div>
	</div>
  </div>
</div>

<div class="component">
  <div class="w-[390px] h-[251px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[30px] inline-flex">
	<img class="w-[50px] h-[50px]" src={icons8_phone_256} />
	<div class="w-[350px] h-[131px] left-0 flex-col justify-start items-center flex">
	  <div class="self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px]">Task Manager</div>
	  <div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Organize your workload, track progress, and collaborate effectively with our intuitive task manager.</div>
	</div>
  </div>   
</div>

<div class="component">
  <div class="w-[390px] h-[292px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[30px] inline-flex">
	<img class="w-[60px] h-[60px]" src={icons8_call} />
	<div class="w-[350px] h-[162px] left-0 flex-col justify-start items-center flex">		
	  <div class= "self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px] ">Video Call</div>
	  <div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Host clear, engaging video conferences with screen sharing, fostering stronger relationships and enhancing communication.</div>	
	</div>
   </div> 
  </div>
</div>

<style lang="postcss">
	:global(html) {
	  background-color: theme(colors.gray.100);
	}

	.all{
		width:  390px;
		height: 2,980px;
		gap: 40px;		
	}
	.componentExternal{
		width: Hug (390px)px;
        height: Hug (578px)px;
        padding: 5px 0px 20px 125px;
        gap: 0px;
        border-radius: 24px 0px 0px 0px;
        opacity: 0px;
	}
	.component{
		width: Fill (390px)px;
        height: Hug (412px)px;
        padding: 20px 125px 20px 125px;
        gap: 60px;
        border-radius: 24px 0px 0px 0px;
        opacity: 0px;
	}	
</style>