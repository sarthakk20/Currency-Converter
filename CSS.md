#CSS

```style.css

body {
	background-color: aliceblue;
	background-position: center;
	background-size: cover;
	background-attachment: fixed;
	background-repeat: no-repeat;
}

.heading {
	font-family: 'Carter One';  /*'Pacifico', cursive;*/
	margin: 35px auto 20px;
    font-weight: 700;
}

.main {
	width: 50vw;
	margin: auto;
	padding: 30px;
	border-radius: 5px;
	background-color: rgba(0, 0, 0, 0.5);
	color: white;
}

label {
	font-size: 20px;
}

.btn {
	width: 200px;
}

#finalAmount {
	font-family:'Protest Riot';/*'Lobster', cursive;*/
	display: none;
	margin: 50px auto;
}

#finalAmount h2 {
	font-size: 50px;
}

.finalValue {
	font-family:'Protest Riot'; /*'Amiri', serif;*/
}

/*Responsiveness*/

@media (max-width: 768px) {
	.main {
		width: 100%;
	}
}
@media (max-width: 400px) {
	.heading {
		font-size: 60px;
	}
	#finalAmount h2,
	.finalValue {
		font-size: 40px;
	}
}   

```
