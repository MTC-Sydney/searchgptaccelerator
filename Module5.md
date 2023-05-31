![MTC Header](./media/image2.jpeg)

# Module 5: Change the predefined questions
By now you have a working application but you notice that the starting questions are not helpful.

Using Visual Studio Code, look in the file `app\frontend\src\components\Example\ExampleList.tsx`

Find the section that's similar to the below and change the text and value pairs to match the top three questions your chat is most likely to be asked. The below examples are related to a sustainability example.

```
const EXAMPLES: ExampleModel[] = [
    {
        text: "What are the sustainability goals?",
        value: "What are the sustainability goals?"
    },
    { text: "What happens in a performance review?", value: "What happens in a performance review?" },
    { text: "What does a Product Manager do?", value: "What does a Product Manager do?" }
];
```

## Redeploy & Test

In Visual Studio Code, right click the yaml file and click *up* 

This step can take a while. 

![Redeploy from Visual Studio Code](./media/codedeployyaml.png)

If all goes well, use the link provided in the output of the deployment and test that the chat interface works as intended. 

![Footer](./media/image3.png)