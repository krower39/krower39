### Hi there 👋

           .grid{
                display: grid;
                grid-template-columns: 200px 1fr 200px;
                grid-template-rows: auto 1fr auto;
                gap: 5px;
                height: 90vh;
            }
            header, footer{
                grid-column: 1 / 4;
                
            }
            header, aside, article, footer{
                border-style: solid;
                background: green;
                font-size: 2em

            }
        </style>
    
