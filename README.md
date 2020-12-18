e1
<!DOCTYPE html>
<script>
	var value=Math.floor((Math.random()*10)+1);
	var guess=window.prompt("please enter your guess(1-10)");
	var flag=1;
	while(flag==1){
		if(guess==value){
		document.writeln("you got it!");
		flag=0
		}else{
			guess=window.prompt("try again!");
		}
	}
	

</script>
