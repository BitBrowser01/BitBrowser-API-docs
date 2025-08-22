Local Service Guide (Demo Download)

<span style="color:hsl(0, 0%, 0%);"><strong>Learn More BitBrowser API：</strong></span><a target="_blank" rel="noopener noreferrer" href="https://doc.bitbrowser.net/api-docs/example-of-interface-request-parameters">https://doc.bitbrowser.net/</a>

Do you want to join the group chat?
If you would like to join the [API Developers] group (for developers only; non-developers will be removed), or the [Custom Script Development] group, please click here to contact customer service, and we will arrange for you to join the group!

Kind reminder: Please select the appropriate group according to your needs to ensure the relevance and quality of the communication.

Introduction
Call the local API to operate the app to open, configure the proxy, etc., to help users realize the automatic script function.

JavaScript demo
Note: The request data is only for demo, for details, please refer to the API document.

archive
Python demo
Note: The request data is only for demo, for details, please refer to the API document.

archive
Postman debug demo, import to use
27KB
Bitnet Export.postman_collection.json
Service Introduction
Support the use of browser functions via Local API to help users run their own automation scripts.

How to use
Install and log in to BitBrowser.

To Settings, find Local API url and port.

Download and run demo.

Interface instructions
Request method is post, and the parameter passing method is responseBody.

The interface returns a json object, success is true and the operation is successful. If there is any returned data, it will be appended to the data object

When the interface returns success as false, it means that the business failed, which may be due to program reasons or parameter verification, etc., and the failure information will be appended to msg# BitBrowser-API-docs
BitBrowser provides a free interface to meet developers' customized needs.

// success example
{
  success: true,
  data: {
    id: '2c9c29a28sdd33dds8026f78e380142',
    groupName: 'name'
  }
}

// failed example
{ success: false, msg: 'Id is required' }

<img width="1544" height="1147" alt="image" src="https://github.com/user-attachments/assets/26a2d263-448a-417f-b926-833d080c2fff" />

<span style="color:hsl(0, 0%, 0%);"><strong>Learn More BitBrowser API：</strong></span><a target="_blank" rel="noopener noreferrer" href="https://doc.bitbrowser.net/api-docs/example-of-interface-request-parameters">https://doc.bitbrowser.net/</a>

