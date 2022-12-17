
#salary{
    background-color: lightblue;
    
    height: 100vh;

}
h1{
	padding-top: 30px;
	margin:0 auto;
	text-align: center;
}
.form{
	display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    flex-direction: row;
}
form{
	margin-top: 50px;

}
.txt{
	border-radius: 10px;
	border: none;
	width: 200px;
	height: 20px;
}
.table{
	display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    flex-direction: row;
}
table{
	margin-top: 50px;
}
p{
	text-align: center;
}
.btn{
    background-color: aqua;
    border-radius: 30px;
    height: 50px;
    border: none;
    position: relative;
    left: 50%;
    transform: translate(-50%, 0);
    width: 200px;
}
.btn:hover{
filter: sepia(1);
}
.btn:active{
	filter: sepia(0);
	background-color:lightblue;
	color:lightblue;
}

.remove{
    background-color: aqua;
    border: none;
   


}
.remove:hover{
	filter: sepia(1);
}
.remove:active{
	filter: sepia(0);
	background-color:lightblue;
	color:lightblue;
}







@media screen and (max-width:700px;){
	#salary{
		width: 650px;
	}
	.form{
		width: 650px;
		height: 400px;
	}
	.table{
		width: 650px;
		height: 400px;
	}
}
