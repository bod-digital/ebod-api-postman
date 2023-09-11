# EBOD API Postman

[Postman](https://getpostman.com) is an API Collaboration Platform.

EBOD offers several Postman Collections and Environments (JSON files) for a quicker and easier usage of our RESTful APIs.<br/>
You only need to import and set up with your own API and secret keys to begin.

## How to import and configure
- Download the `ebod-api-postman` repository.

- Click the `Import` button. On Postman for Mac, for example, the button is at the top left:
![image](https://github.com/bod-digital/ebod-api-postman/assets/142394627/24fc2de1-3773-4a05-a80e-583dc47300a4)

- On the `Import` pop-up page, select the `Folder` tab. Click the `Choose folder from your computer` button and choose the root folder of the downloaded repository.
![image](https://github.com/bod-digital/ebod-api-postman/assets/142394627/e6e50e19-8724-4d43-bbea-ae464a0ad37b)

- Select which collections and environments you would like to import and click the `Import` button.
![image](https://github.com/bod-digital/ebod-api-postman/assets/142394627/de35c332-7eeb-4329-a58c-8a9d2b18ccc1)

- Select the `Collections` tab on the left, choose an `EBOD API`, then select `Authorization` tab and select `Bearer Token` type and set your Token by changing the `Token value` input (see screenshot);
![image](https://github.com/bod-digital/ebod-api-postman/assets/142394627/31fd9529-d999-4159-8b49-229d0e553822)
  

## Postman safety practices
The following practices are advised to secure your account's safety:

- Don't use Collections obtained from an unknown source.
- Review the environment JSON file before its usage.
- Don't use any code that you don't understand.
- When you finish trying out the API, delete your API keys.

## FAQ
**Q:** Why I can't get any response?

You haven't imported the environment file or you've imported it but haven't selected it from the dropdown menu (mentioned in [[How to import and configure]])

**Q:** How can I debug a request or find the used URL?

- Open the Postman's console to find requests' parameters and URL.
- Debugging can be done by editing the `Pre-request Script` tab.

**Q:** Error `Forbidden`

Likely causes:
- Authorization header is not set.
- API key is not set.
- API key is not correct.

**Q:** Error `Invalid input data` or `Invalid event type`

Please refer to the API documentation to double check all the mandatory parameters.


## My question isn't here
If you don't find your answer here, please consult https://discord.gg/SyejrseM for similar questions from the API support discord group or open an issue https://github.com/bod-digital/ebod-api-postman/issues.
