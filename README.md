# CookLine

This is a simple cooking app that uses node.js, express, ejs and the Facebook client-side JS SDK to demonstrate simple Open Graph principles.

Tested and runs against the Heroku cedar stack, as per http://devcenter.heroku.com/articles/nodejs

The application requires the following environment variables:

    APP_ID=<fb_app_id>
    APP_DOMAIN=<fb_app_domain>
    APP_NS=<fb_app_open_graph_namespace>

For example, the canonical instance of the application uses:

    APP_ID=294113397324835
    APP_DOMAIN=https://cookline.herokuapp.com
    APP_NS=cookline

(You will have to use different values for all three of these properties to suit your own app's configuration)

You set these variables in the .env file of a local install, or on heroku through the use of the following command:

    heroku config:add APP_ID=<fb_app_id>

etc

## Licence

Copyright 2012 Facebook, Inc.

You are hereby granted a non-exclusive, worldwide, royalty-free license to
use, copy, modify, and distribute this software in source code or binary
form for use in connection with the web services and APIs provided by
Facebook.

As with any software that integrates with the Facebook platform, your use
of this software is subject to the Facebook Developer Principles and
Policies [http://developers.facebook.com/policy/]. This copyright notice
shall be included in all copies or substantial portions of the software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
