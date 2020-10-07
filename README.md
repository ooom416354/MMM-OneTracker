## MMM-OneTracker

Track all your deliveries in one module. Supports 428 couriers worldwide.

## Here's what you get

A rotation of all your deliveries that are currently in transit.
Status, estimated delivery date, which courier, tracking number, etc. . .
UPS, FedEx, USPS, etc.. Very handy during the holiday season when you have
multiple deliveries coming by multiple couriers.

## Examples

- Annotated .css file included for coloring any way you like.

![](images/1.JPG) ![](images/2.JPG) ![](images/4.JPG)

![](images/3.JPG)

## Installation

- `git clone https://github.com/mykle1/MMM-OneTracker` into the `~/MagicMirror/modules` directory.

- Get your FREE API Key from https://www.OneTracker.com/

- You MUST add couriers to your account at OneTracker.com. It's easy and FREE!

## Config.js entry and options

    {
        disabled: false,
        module: "MMM-OneTracker",
        position: "top_left",
        config: {
            apiKey: "Your API Key GOES HERE",  // Your free API Key from OneTracker.com
            apiLanguage: "en",
            useHeader: true,                   // False if you don't want a header
            header: "OneTracker Tracking",      // Change in config file. useHeader must be true
            maxWidth: "300px",
            animationSpeed: 3000,              // fade speed
            rotateInterval: 30 * 1000,         // seconds between shipments
            dateTimeFormat: "ddd, MMM DD, YYYY, h:mm a",
            dateFormat: "ddd, MMM DD, YYYY"
        }
    },

## Is there a module that SpaceCowboysDude hasn't fixed for you, Mykle? :^)
