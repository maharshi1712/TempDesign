<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@600&family=Roboto:wght@700&display=swap');
        .wrapper {
            display: flex;
            align-items: flex-end;
            min-height: 100vh;
            color: #132743;
        }
        
        .box1 {
            align-self: stretch;
            width: 6%;
            background-color: #F8EFD4;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        
        .box2 {
            align-self: stretch;
            background-image: url('./Group\ 875.png');
            width: 70%;
        }
        
        .box3 {
            align-self: stretch;
            width: 24%;
            background-image: url('./ezgif.com-gif-maker.png');
            background-repeat: no-repeat;
            background-size: cover;
        }
        
        .icons {
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            margin-top: auto;
            margin-bottom: 30px;
        }
        
        .icons li {
            padding-top: 19px;
            list-style: none;
        }
        
        .icons li svg path:hover {
            fill: #102138;
        }
        
        .logo {
            margin-top: 39px;
        }
        
        .nav-bar {
            display: flex;
            align-items: center;
            padding: 30px;
        }
        
        p {
            font-family: 'Roboto', sans-serif;
        }
        
        .nav-items {
            font-size: 24px;
            margin-left: auto;
        }
        
        .nav-items ui li {
            display: flex;
            flex-direction: row;
        }
        
        .bubble {
            position: absolute;
            left: 57.81%;
            right: 36.25%;
            top: 32.98%;
            bottom: 50.46%;
        }
        
        h1 {
            font-family: 'Raleway', sans-serif;
            font-size: 100px;
            padding-left: 30px;
        }
        
        .basic-addon2 {
            background-color: #D7385E;
        }
        
         :root {
            --input-color: #102138;
            --input-border: #D7385E;
            --input-background: #fff;
            --input-placeholder: #CBD1DC;
            --input-border-focus: #102138;
            --group-color: var(--input-color);
            --group-border: var(--input-border);
            --group-background: #D7385E;
            --group-color-focus: #fff;
            --group-border-focus: var(--input-border-focus);
            --group-background-focus: #102138;
        }
        
        .form-field {
            display: block;
            width: 100%;
            padding: 8px 16px;
            line-height: 25px;
            font-size: 14px;
            font-weight: 500;
            font-family: inherit;
            -webkit-appearance: none;
            color: var(--input-color);
            border: 2px solid var(--input-border);
            background: var(--input-background);
            transition: border 0.3s ease;
        }
        
        .form-field::placeholder {
            color: var(--input-placeholder);
        }
        
        .form-field:focus {
            outline: none;
            border-color: var(--input-border-focus);
        }
        
        .form-group {
            position: relative;
            display: flex;
            width: 70%;
            padding-left: 30px;
            margin-top: 50px;
        }
        
        .form-group>span,
        .form-group .form-field {
            white-space: nowrap;
            display: block;
        }
        
        .form-group>span:not(:first-child),
        .form-group .form-field:not(:first-child) {
            margin-left: -1px;
        }
        
        .form-group .form-field {
            position: relative;
            z-index: 1;
            flex: 1 1 auto;
            width: 1%;
            margin-top: 0;
            margin-bottom: 0;
        }
        
        .form-group>span {
            text-align: center;
            padding: 12px 17px;
            font-size: 14px;
            line-height: 25px;
            color: var(--group-color);
            background: var(--group-background);
            border: 1px solid var(--group-border);
            transition: background 0.3s ease, border 0.3s ease, color 0.3s ease;
        }
        
        .form-group:focus-within>span {
            color: var(--group-color-focus);
            background: var(--group-background-focus);
            border-color: var(--group-border-focus);
        }
        
        .side {
            width: 800px;
            height: 232px;
            background-color: #132743;
            position: absolute;
            left: 1000px;
            top: 600px;
            display: flex;
            color: #fff;
            justify-content: center;
            align-items: center;
            padding-left: 50px;
        }
        
        .big {
            font-size: 56px;
            color: #EDC988;
            font-family: sans-serif;
            font-weight: lighter;
        }
        
        .big-text {
            color: #fff;
            font-family: sans-serif;
            font-weight: normal;
        }
    </style>
</head>

<body>
    <div class="wrapper">
        <div class="box1">
            <svg class="logo" width="58" height="58" viewBox="0 0 58 58" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M28.98 0C57.4 0 57.961 12.975 57.961 28.98C57.961 44.985 57.361 57.96 28.981 57.96C0.601002 57.96 0 44.986 0 28.98C0 12.974 0.562 0 28.98 0Z" fill="#132743"/>
            </svg>
            <ui class="icons">
                <li>
                    <a href="#">
                        <svg width="24" height="25" viewBox="0 0 24 25" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M20.01 15.981C18.8113 15.9803 17.6201 15.7914 16.48 15.421C16.3061 15.362 16.1191 15.3533 15.9405 15.3957C15.7618 15.4382 15.5988 15.5301 15.47 15.661L13.9 17.631C10.9182 16.1691 8.49792 13.7699 7.01 10.801L8.96 9.14095C9.08843 9.00849 9.17857 8.84369 9.22083 8.66409C9.26309 8.48449 9.25589 8.29679 9.2 8.12095C8.82478 6.98204 8.63569 5.79007 8.64 4.59095C8.6374 4.3292 8.53226 4.0789 8.34716 3.8938C8.16206 3.7087 7.91176 3.60356 7.65 3.60095H4.19C3.65 3.60095 3 3.84095 3 4.59095C3.0371 9.09081 4.84114 13.3958 8.02312 16.5778C11.2051 19.7598 15.5101 21.5638 20.01 21.601C20.1545 21.594 20.296 21.5572 20.4255 21.4929C20.5551 21.4286 20.67 21.3382 20.763 21.2274C20.856 21.1166 20.925 20.9877 20.9658 20.849C21.0066 20.7102 21.0182 20.5645 21 20.421V16.971C20.9974 16.7092 20.8923 16.4589 20.7072 16.2738C20.5221 16.0887 20.2718 15.9836 20.01 15.981Z" fill="#132743"/>
                        </svg>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <svg width="26" height="26" viewBox="0 0 26 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M23.755 0.26294H1.847C1.6045 0.262808 1.36434 0.31046 1.14026 0.403171C0.916177 0.495882 0.712557 0.631837 0.541034 0.803267C0.369512 0.974697 0.233447 1.17824 0.140614 1.40228C0.0477813 1.62631 -3.55816e-08 1.86644 0 2.10894L0 24.0169C-3.55816e-08 24.2594 0.0477813 24.4996 0.140614 24.7236C0.233447 24.9476 0.369512 25.1512 0.541034 25.3226C0.712557 25.494 0.916177 25.63 1.14026 25.7227C1.36434 25.8154 1.6045 25.8631 1.847 25.8629H23.755C24.2444 25.8627 24.7137 25.6681 25.0597 25.3219C25.4056 24.9757 25.6 24.5064 25.6 24.0169V2.10894C25.6 1.61952 25.4056 1.15014 25.0597 0.803974C24.7137 0.457811 24.2444 0.263205 23.755 0.26294V0.26294ZM9.081 19.6129H5.963V10.2349H9.081V19.6129ZM7.522 8.95394H7.5C7.27698 8.96733 7.0536 8.93459 6.84381 8.85777C6.63401 8.78094 6.44232 8.66168 6.28069 8.50743C6.11906 8.35319 5.99098 8.16727 5.90444 7.96129C5.8179 7.75531 5.77477 7.5337 5.77773 7.3103C5.7807 7.08691 5.82969 6.86652 5.92167 6.66291C6.01364 6.4593 6.14661 6.27685 6.31227 6.12694C6.47793 5.97704 6.67273 5.8629 6.88449 5.79167C7.09625 5.72044 7.32042 5.69363 7.543 5.71294C7.76603 5.69782 7.98978 5.72888 8.20026 5.80418C8.41074 5.87948 8.60342 5.9974 8.76625 6.15056C8.92908 6.30371 9.05856 6.48882 9.14659 6.6943C9.23462 6.89978 9.27931 7.12121 9.27786 7.34475C9.27641 7.56829 9.22885 7.78912 9.13817 7.99344C9.04748 8.19776 8.91562 8.38118 8.75082 8.53221C8.58601 8.68325 8.39182 8.79866 8.18039 8.87122C7.96895 8.94379 7.74482 8.97195 7.522 8.95394V8.95394ZM20.322 19.6139H17.2V14.5959C17.2 13.3349 16.749 12.4749 15.621 12.4749C15.2694 12.477 14.9269 12.5876 14.6406 12.7917C14.3542 12.9957 14.1378 13.2833 14.021 13.6149C13.942 13.8605 13.9081 14.1183 13.921 14.3759V19.6129H10.806C10.806 19.6129 10.847 11.1129 10.806 10.2339H13.923V11.5629C14.2056 11.0733 14.6166 10.6703 15.1117 10.3974C15.6069 10.1246 16.1671 9.99232 16.732 10.0149C18.783 10.0149 20.321 11.3549 20.321 14.2359L20.322 19.6139Z" fill="#132743"/>
                        </svg>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <svg width="26" height="26" viewBox="0 0 26 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M18.164 0.399902H7.437C5.46523 0.40202 3.57483 1.18624 2.18059 2.58049C0.786336 3.97474 0.00211762 5.86514 0 7.8369V18.5639C0.00238225 20.5355 0.786718 22.4256 2.18094 23.8197C3.57516 25.2137 5.46541 25.9978 7.437 25.9999H18.164C20.1354 25.9975 22.0254 25.2133 23.4194 23.8193C24.8134 22.4253 25.5976 20.5353 25.6 18.5639V7.8369C25.5979 5.86531 24.8138 3.97506 23.4198 2.58084C22.0257 1.18662 20.1356 0.402285 18.164 0.399902V0.399902ZM23.6 18.5639C23.5981 20.0051 23.0248 21.3866 22.0058 22.4057C20.9867 23.4247 19.6051 23.9981 18.164 23.9999H7.437C5.99568 23.9983 4.61383 23.4251 3.59457 22.406C2.5753 21.387 2.00185 20.0052 2 18.5639V7.8369C2.00159 6.39541 2.57492 5.01341 3.59421 3.99412C4.61351 2.97483 5.99551 2.40149 7.437 2.3999H18.164C19.6053 2.40176 20.9871 2.97521 22.0061 3.99447C23.0252 5.01373 23.5984 6.39558 23.6 7.8369V18.5639Z" fill="#132743"/>
                            <path d="M12.8 6.29993C11.4353 6.29993 10.1013 6.7046 8.96657 7.46278C7.83187 8.22097 6.94748 9.2986 6.42523 10.5594C5.90299 11.8202 5.76635 13.2076 6.03259 14.5461C6.29882 15.8845 6.95599 17.114 7.92097 18.079C8.88595 19.0439 10.1154 19.7011 11.4539 19.9673C12.7924 20.2336 14.1797 20.0969 15.4405 19.5747C16.7013 19.0524 17.779 18.1681 18.5371 17.0334C19.2953 15.8987 19.7 14.5646 19.7 13.1999C19.6979 11.3706 18.9702 9.61677 17.6767 8.32323C16.3832 7.02968 14.6293 6.30204 12.8 6.29993V6.29993ZM12.8 18.0999C11.8309 18.0999 10.8835 17.8125 10.0777 17.2741C9.27191 16.7357 8.64387 15.9704 8.273 15.0751C7.90213 14.1797 7.80509 13.1945 7.99416 12.244C8.18323 11.2935 8.6499 10.4204 9.33518 9.7351C10.0205 9.04982 10.8936 8.58315 11.8441 8.39408C12.7946 8.20501 13.7798 8.30205 14.6751 8.67292C15.5705 9.04379 16.3358 9.67183 16.8742 10.4776C17.4126 11.2834 17.7 12.2308 17.7 13.1999C17.6984 14.499 17.1817 15.7444 16.2631 16.663C15.3445 17.5816 14.0991 18.0983 12.8 18.0999V18.0999Z" fill="#132743"/>
                            <path d="M20 7.31891C20.5523 7.31891 21 6.87119 21 6.31891C21 5.76662 20.5523 5.31891 20 5.31891C19.4477 5.31891 19 5.76662 19 6.31891C19 6.87119 19.4477 7.31891 20 7.31891Z" fill="#132743"/>
                        </svg>
                    </a>
                </li>
            </ui>
        </div>
        <div class="box2">
            <div class="nav-bar">
                <p class="logo_name" style="font-size:56px;">
                    Localorr
                </p>
                <div class="nav-items">
                    <a href="#" style="color:#132743;">ABOUT US</a>
                    <a href="#" style="color:#D7385E;padding-left:40px;">LOG IN</a>
                </div>
            </div>
            <svg class="bubble" width="218" height="176" viewBox="0 0 218 176" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M99 150C130.48 150 156 124.48 156 93C156 61.5198 130.48 36 99 36C67.5198 36 42 61.5198 42 93C42 124.48 67.5198 150 99 150Z" fill="#D7385E"/>
                <path d="M74.5 17C79.1944 17 83 13.1944 83 8.5C83 3.80558 79.1944 0 74.5 0C69.8056 0 66 3.80558 66 8.5C66 13.1944 69.8056 17 74.5 17Z" fill="#D7385E"/>
                <path opacity="0.3" d="M46.5 77C51.1944 77 55 73.1944 55 68.5C55 63.8056 51.1944 60 46.5 60C41.8056 60 38 63.8056 38 68.5C38 73.1944 41.8056 77 46.5 77Z" fill="#D7385E"/>
                <path d="M211 93C214.866 93 218 89.866 218 86C218 82.134 214.866 79 211 79C207.134 79 204 82.134 204 86C204 89.866 207.134 93 211 93Z" fill="#D7385E"/>
                <path d="M73 176C76.866 176 80 172.866 80 169C80 165.134 76.866 162 73 162C69.134 162 66 165.134 66 169C66 172.866 69.134 176 73 176Z" fill="#D7385E"/>
                <path opacity="0.5" d="M176 28C179.866 28 183 24.866 183 21C183 17.134 179.866 14 176 14C172.134 14 169 17.134 169 21C169 24.866 172.134 28 176 28Z" fill="#D7385E"/>
                <path d="M14.5 169C22.5081 169 29 162.508 29 154.5C29 146.492 22.5081 140 14.5 140C6.49187 140 0 146.492 0 154.5C0 162.508 6.49187 169 14.5 169Z" fill="#D7385E"/>
                <path opacity="0.3" d="M161.5 155C169.508 155 176 148.508 176 140.5C176 132.492 169.508 126 161.5 126C153.492 126 147 132.492 147 140.5C147 148.508 153.492 155 161.5 155Z" fill="#D7385E"/>
            </svg>
            <h1>One-stop destination to support Locals</h1>
            <div class="form-group">
                <input class="form-field" type="email" placeholder="Search for Shops / Category">
                <span>
                    <svg width="25" height="25" viewBox="0 0 25 25" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.9141 8.823C12.1229 8.823 11.3496 9.05759 10.6918 9.49712C10.034 9.93665 9.52129 10.5614 9.21854 11.2923C8.91579 12.0232 8.83658 12.8274 8.99092 13.6034C9.14526 14.3793 9.52623 15.092 10.0856 15.6514C10.645 16.2108 11.3578 16.5918 12.1337 16.7461C12.9096 16.9005 13.7139 16.8213 14.4448 16.5185C15.1757 16.2158 15.8004 15.7031 16.2399 15.0453C16.6795 14.3875 16.9141 13.6141 16.9141 12.823C16.9141 11.7621 16.4926 10.7447 15.7425 9.99457C14.9923 9.24443 13.9749 8.823 12.9141 8.823V8.823ZM21.8541 11.823C21.6276 9.79512 20.7182 7.90454 19.2754 6.46169C17.8325 5.01885 15.9419 4.10951 13.9141 3.883V1.823H11.9141V3.883C9.88618 4.10951 7.9956 5.01885 6.55276 6.46169C5.10991 7.90454 4.20057 9.79512 3.97406 11.823H1.91406V13.823H3.97406C4.20057 15.8509 5.10991 17.7415 6.55276 19.1843C7.9956 20.6271 9.88618 21.5365 11.9141 21.763V23.823H13.9141V21.763C15.9419 21.5365 17.8325 20.6271 19.2754 19.1843C20.7182 17.7415 21.6276 15.8509 21.8541 13.823H23.9141V11.823H21.8541V11.823ZM12.9141 19.823C11.5296 19.823 10.1762 19.4125 9.02507 18.6433C7.87393 17.8741 6.97672 16.7809 6.44691 15.5018C5.91709 14.2227 5.77847 12.8152 6.04857 11.4574C6.31866 10.0995 6.98535 8.85222 7.96431 7.87325C8.94328 6.89428 10.1906 6.2276 11.5484 5.9575C12.9063 5.6874 14.3138 5.82603 15.5928 6.35584C16.8719 6.88565 17.9652 7.78286 18.7344 8.93401C19.5035 10.0852 19.9141 11.4385 19.9141 12.823C19.9147 13.7424 19.7341 14.653 19.3826 15.5026C19.031 16.3521 18.5154 17.1241 17.8653 17.7742C17.2151 18.4244 16.4432 18.9399 15.5936 19.2915C14.744 19.643 13.8335 19.8237 12.9141 19.823Z" fill="white"/>
                    </svg>     
                     Locate me
                </span>
            </div>
            <div class="side">
                <div class="col">
                    <span class="big">100+</span>
                    <p class="big-text">Local stores to choose from!</p>
                </div>
                <div class="col">
                    <span class="big">3k+</span>
                    <p class="big-text">Active DailyCustomers</p>
                </div>
            </div>
        </div>
        <div class="box3"></div>
    </div>

</body>

</html>
