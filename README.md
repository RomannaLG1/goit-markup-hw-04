# goit-markup-hw-04
.contacts-nav-item::before {
	display: block;
	content: "";

	align-self: center;
	margin-right: 10px;
	background-color: var(--primare-bg-color);

	background-repeat: no-repeat;
	background-position: center;
	/* outline: 1px solid tomato; */
}

.icon-envelope::before {
	width: 16px;
	height: 12px;
	background-image: url(../image/envelope.svg);
	background-size: 16px 12px;
}

.icon-phone::before {
	width: 10px;
	height: 16px;
	background-image: url(../image/smartphone.svg);
	background-size: 10px 16px;
}


.feature-list-item::before {
	display: block;
	margin-bottom: var(--card-set-gap);
	content: "";

	background-repeat: no-repeat;
	background-position: center;
	background-size: 70px 70px;
	background-color: var(--secondary-bg-color);
	border-radius: 4px;

	height: 120px;
	/* outline: 1px solid tomato; */
}

.icon-antena::before {
	background-image: url(../image/antena.svg);
}
.icon-clock::before {
	background-image: url(../image/clock.svg);
}
.icon-diagram::before {
	background-image: url(../image/diagram.svg);
}
.icon-astronaut::before {
	background-image: url(../image/astronaut.svg);
