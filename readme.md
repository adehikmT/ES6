## ES6 
ES6 adalah suatu penulisan sintak javascript moderen yang dapat membantu dalam menuliskan sintax javascript.
hal yang ada dalam ES6 :
+ penulisan variable
   di ES6 kita akan menemukan let dan const selain var, kegunaan dari masing-masing variable tersebut juga berbeda. let dan var kendatinya sama mereka bisa merubah suatu nilai jika suaktu waktu variable nya di ubah namun yang membedakan let dan var adalah global scoup varable.
   
   let nama="ade";
   var umur=18;
   {
   	console.log(umur); //tiak akan error 
   	console.log(nama); //error karena scoupnya berbeda	
   }

+ default parameter
  di ES6 kita bisa memberi default paramater dengan sangat mudah;

  //ES6
  jumlah=(x=0,y=0)=>(x+y)

  //javascript
  function jumlah(x,y){ 
	this.x=x
	this.y=y

    if(x=="undifind"){
    	x=0;
    }
	if(x=="undifind"){
    	y=0;
    }    
   return x+y;
  }

+ arrow
   arrow ini di gunakan untuk mempersingkat penulisan fungsi . untuk contoh :
   
   //ES6
   HalloWorld=()=>{
   console.log("hallo world")
   }
   
   //javascript
   function HalloWorld(){
   console.log("hallo world")
   }

   //ES6 
   Jumlah=(x,y)=>(x+y)
   
   //javascript
   function Jumlah(x,y)
   {
    this.x=x;
    this.y=y;
    return x+y;
   }

+ rest dan spread
   HalloNama=(nama,nama2)=>{
   console.log("hallo "+nama+"hallo "+nama2);
   }
   nama=["ade","hikmat"];
   HalloNama(...nama);

   //dan

   HalloName=(...nama)=>{
   console.log(nama); //bentuk array
   }

+ template literal
  jadi kita bisa menggabungkan string dan juga nama variable tampa oprator konket dengan menggunakan backtip `${namavariable}` 
  
  let nama="ade"
  let text=`hallo ${ade}`

