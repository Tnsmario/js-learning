I don't know how to change the code so it tells me how many bottles are left. For example if 45 bottles are on the wall, it will still be showing me that 45 bottles are left on the wall. So basicly all i need to do is to decrease oen after each bottles are "consumed".


# js-learning

var output = [];
var count = 99;

function beer(){
    while(count >= 0){
    if(count >= 1){
        console.log(count + " bottles of beer on the wall, " + count + " bottles of beer. Take one down and pass it around, " + count + " bottles of beer on the wall.")
    }
    if(count === 0){
        console.log("No more bottles of beer on the wall, no more bottles of beer. Go to the store and buy some more, 99 bottles of beer on the wall.")
    }
    count--;
    }
}
