# Sample1
Test For Projects
.accordions {
    color: black;
		font-family: 'Linus Libertine', 'Georgia', 'Times',serif;
		font-size: 24px!important;
		margin-bottom: .25em!important;
		font-weight: normal!important;
		border-style:none;
		line-height: 1.4em;
    cursor: pointer;
    width: 100%;
    text-align: left;
    outline: none;
    font-size: 15px;
    transition: 0.4s;
}

.activeaccordion, .accordions:hover {
    background-color: #ccc;
}

.accordions:before {
    content: '\002B';
    color: #777;
    font-weight: bold;
    margin-right: 5px;
}
.activeaccordion:before {
    content: "\2212";
}
.panelst {
    padding: 0 18px;
    background-color: white;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.2s ease-out;
}
