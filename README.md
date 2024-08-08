# ARCHIVED

This repo has been archived and is no longer maintained. We recommend using the Slack tools in [gptscript-ai/integrations](https://github.com/gptscript-ai/integrations).

# slack-message

This is a simple GPTScript tool to send a Slack message to a channel.

## Setup and Usage

1. Create a new Slack app in your workspace.
2. Under the OAuth & Permissions settings, give your app the following User Token scopes:
   - `channels:read`
   - `chat:write`
3. Install the app to your workspace.
4. Get your User OAuth Token from the app's OAuth & Permissions settings.
5. Set the token to the environment variable `GPTSCRIPT_SLACK_TOKEN`.
6. Now you can use the tool in a script:

```
Tools: github.com/gptscript-ai/slack-message

Send a message to the general channel saying "hello from gptscript".
```

## License

Copyright (c) 2024 [Acorn Labs, Inc.](http://acorn.io)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
