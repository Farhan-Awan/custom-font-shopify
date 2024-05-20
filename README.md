# custom-font-shopify
how to install custom fonts in shopify with code example



@font-face {
    font-family: 'Floki';
    src: url("https://cdn.shopify.com/s/files/1/0596/1898/4089/files/Floki-Bold.woff?v=1716232914") format('woff'),
        url("https://cdn.shopify.com/s/files/1/0596/1898/4089/files/Floki-Bold.woff2?v=1716232914") format('woff2');
    font-weight: bold;
    font-style: normal;
    font-display: swap;
}
h1, h2, h3 {
  font-family : 'Floki'!important;
  text-transform: uppercase;
    font-size: 50px;
}
