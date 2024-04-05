# React and complimentary libraries

React is a library and not a framework. This means you'll often use other JavaScript libraries with it to build your application. In this reading, you will be briefly introduced to some JavaScript libraries commonly used with React.

**Lodash**

<span><a target="_blank" rel="noopener nofollow noreferrer" href="https://lodash.com/" class="css-gcjbqe"><span><span>Official Website</span></span><svg aria-labelledby="cds-react-aria-37-title" fill="none" focusable="false" height="16" role="img" viewBox="0 0 16 16" width="16" class="css-1lzqdox" id="cds-react-aria-37"><title id="cds-react-aria-37-title">Opens in a new tab</title><path fill-rule="evenodd" clip-rule="evenodd" d="M1.5 3.5H6v1H2.5v9h9V10h1v4.5h-11v-11zM13.5 2.5H10v-1h4.5V6h-1V2.5z" fill="currentColor"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M6.646 8.646l7-7 .708.708-7 7-.708-.708z" fill="currentColor"></path></svg></a></span>

As a developer, there's a lot of logic you'll commonly write across applications. For example, you might need to sort a list of items or round a number such as `3.14` to `3`. Lodash provides common logic such as these as a utility library to save you time as a developer.

<figure role="figure" contenteditable="false"><img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/6PPhvQmNRMmz4b0JjSTJAg_2fa2b1bd3ab94ace92fd29cc0f2552e1_lodash.png?expiry=1712448000000&amp;hmac=xFjpHBZJJ_yKFkAsn5lYLnkz4M8xu6sPBgxGCLHdOf8" alt="Other Javascript libraries: Lodash" data-asset-id="6PPhvQmNRMmz4b0JjSTJAg" class="cml-image-default undefined"></figure>

**Luxon**

<span><a target="_blank" rel="noopener nofollow noreferrer" href="https://moment.github.io/luxon/#/" class="css-gcjbqe"><span><span>Official Website</span></span><svg aria-labelledby="cds-react-aria-38-title" fill="none" focusable="false" height="16" role="img" viewBox="0 0 16 16" width="16" class="css-1lzqdox" id="cds-react-aria-38"><title id="cds-react-aria-38-title">Opens in a new tab</title><path fill-rule="evenodd" clip-rule="evenodd" d="M1.5 3.5H6v1H2.5v9h9V10h1v4.5h-11v-11zM13.5 2.5H10v-1h4.5V6h-1V2.5z" fill="currentColor"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M6.646 8.646l7-7 .708.708-7 7-.708-.708z" fill="currentColor"></path></svg></a></span>

You'll be working with dates and times often as a developer. Think of viewing a list of orders and when they were placed, or displaying a calendar schedule for an event. Dates and times are everywhere.

Luxon helps you work with dates and times by providing functions to manipulate and display them. For example, think of how dates are formatted in different countries. In the United States the format is `Month Day Year` but in Europe it is `Day Month Year`. This is one area where Luxon can help you display the date in the user's local format.

<figure role="figure" contenteditable="false"><img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/DJVPki_uTtKVT5Iv7h7SnQ_4e9070251db24d8db87a7ccd13befde1_luxon.png?expiry=1712448000000&amp;hmac=eFuACdt-aX74UamBdGOOFcJmSep1fuSKLLGdRtRjhWc" alt="Other Javascript libraries: Luxon" data-asset-id="DJVPki_uTtKVT5Iv7h7SnQ" class="cml-image-default undefined"></figure>

**Redux**

<span><a target="_blank" rel="noopener nofollow noreferrer" href="https://redux.js.org/" class="css-gcjbqe"><span><span>Official Website</span></span><svg aria-labelledby="cds-react-aria-39-title" fill="none" focusable="false" height="16" role="img" viewBox="0 0 16 16" width="16" class="css-1lzqdox" id="cds-react-aria-39"><title id="cds-react-aria-39-title">Opens in a new tab</title><path fill-rule="evenodd" clip-rule="evenodd" d="M1.5 3.5H6v1H2.5v9h9V10h1v4.5h-11v-11zM13.5 2.5H10v-1h4.5V6h-1V2.5z" fill="currentColor"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M6.646 8.646l7-7 .708.708-7 7-.708-.708z" fill="currentColor"></path></svg></a></span>

When building a web application, you'll need to keep track of its state. Think of when you shop online. The web application tracks items currently in your shopping cart. When you remove an item from the cart, the application needs to update what displays on the screen. This is where Redux comes in. It helps you manage your application state and even has advanced features such as undo and redo.

<figure role="figure" contenteditable="false"><img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/qIYlcXXASmGGJXF1wNpheQ_6685db7e36ad4e888d597c9ab8555ae1_redux.png?expiry=1712448000000&amp;hmac=V_zDnFUHQxM2_mes-0c0lZ2USFZr97KV6CH16L8dTug" alt="Other Javascript libraries: Redux" data-asset-id="qIYlcXXASmGGJXF1wNpheQ" class="cml-image-default undefined"></figure>

**Axios**

<span><a target="_blank" rel="noopener nofollow noreferrer" href="https://axios-http.com/" class="css-gcjbqe"><span><span>Official Website</span></span><svg aria-labelledby="cds-react-aria-40-title" fill="none" focusable="false" height="16" role="img" viewBox="0 0 16 16" width="16" class="css-1lzqdox" id="cds-react-aria-40"><title id="cds-react-aria-40-title">Opens in a new tab</title><path fill-rule="evenodd" clip-rule="evenodd" d="M1.5 3.5H6v1H2.5v9h9V10h1v4.5h-11v-11zM13.5 2.5H10v-1h4.5V6h-1V2.5z" fill="currentColor"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M6.646 8.646l7-7 .708.708-7 7-.708-.708z" fill="currentColor"></path></svg></a></span>

As a developer you'll be communicating with APIs over HTTP frequently. The Axios library helps to simplify sending HTTP requests and processing the response. It also provides advanced features allowing you to cancel requests and to change data received from the web server before your application uses the data.

<figure role="figure" contenteditable="false"><img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/e4ATjMUyQ_GAE4zFMtPx6w_b150947697044d898fae5ad6ae0b4ee1_axios.png?expiry=1712448000000&amp;hmac=9d29WtDCSMput-KqayZsHaZAX8XU0G1u0OE0kIi3cvs" alt="Other Javascript libraries: Axios " data-asset-id="e4ATjMUyQ_GAE4zFMtPx6w" class="cml-image-default undefined"></figure>

**Jest**

<span><a target="_blank" rel="noopener nofollow noreferrer" href="https://jestjs.io/" class="css-gcjbqe"><span><span>Official Website</span></span><svg aria-labelledby="cds-react-aria-41-title" fill="none" focusable="false" height="16" role="img" viewBox="0 0 16 16" width="16" class="css-1lzqdox" id="cds-react-aria-41"><title id="cds-react-aria-41-title">Opens in a new tab</title><path fill-rule="evenodd" clip-rule="evenodd" d="M1.5 3.5H6v1H2.5v9h9V10h1v4.5h-11v-11zM13.5 2.5H10v-1h4.5V6h-1V2.5z" fill="currentColor"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M6.646 8.646l7-7 .708.708-7 7-.708-.708z" fill="currentColor"></path></svg></a></span>

It is good practice to write automated tests for your code as a professional developer. The jest library helps you to do this and works with many libraries and frameworks. It also provides reporting utilities such as providing information on how much of your code is tested by your automated tests.

<figure role="figure" contenteditable="false"><img src="https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/OyjC8JaDR6yowvCWgyeswQ_0a9ae6e00b564488b2683f0612f1e5e1_jest.png?expiry=1712448000000&amp;hmac=uoPynPLgUFGwK3ozNozA886VGzIEZ_onLeMge3Y5ei0" alt="Other Javascript libraries: Jest " data-asset-id="OyjC8JaDR6yowvCWgyeswQ" class="cml-image-default undefined"></figure>

**Conclusion**

If you're curious to learn more about these libraries, their websites feature setup guides, tutorials and documentation to get started. These libraries will be covered later on.