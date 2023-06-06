aaxhrj@gmail.com 
{
  "title": "order-a-coffee",
  "steps": [
    {
      "type": "setViewport",
      "width": 603,
      "height": 679,
      "deviceScaleFactor": 1,
      "isMobile": false,
      "hasTouch": false,
      "isLandscape": false
    },
    {
      "type": "navigate",
      "url": "https://coffee-cart.netlify.app/",
      "assertedEvents": [
        {
          "type": "navigation",
          "url": "https://coffee-cart.netlify.app/",
          "title": "Coffee cart"
        }
      ]
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Mocha"
        ],
        [
          "[data-test=Mocha]"
        ]
      ],
      "target": "main",
      "offsetX": 190.90188598632812,
      "offsetY": 120.25460815429688
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Cafe Latte"
        ],
        [
          "[data-test=Cafe_Latte]"
        ]
      ],
      "target": "main",
      "offsetX": 137.90187072753906,
      "offsetY": 100.47335815429688
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Cart page"
        ],
        [
          "#app > ul > li:nth-child(2) > a"
        ]
      ],
      "target": "main",
      "offsetX": 24.6796875,
      "offsetY": 8.5
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Add one Cafe Latte"
        ],
        [
          "#app > div.list > div > ul > li:nth-child(2) > div:nth-child(2) > div > button:nth-child(1)"
        ]
      ],
      "target": "main",
      "offsetX": 5,
      "offsetY": 7.78125
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Proceed to checkout"
        ],
        [
          "[data-test=checkout]"
        ]
      ],
      "target": "main",
      "offsetX": 148,
      "offsetY": 31.921875
    },
    {
      "type": "click",
      "selectors": [
        [
          "#name"
        ]
      ],
      "target": "main",
      "offsetX": 118.21875,
      "offsetY": 15.90625
    },
    {
      "type": "change",
      "value": "jane",
      "selectors": [
        [
          "#name"
        ]
      ],
      "target": "main"
    },
    {
      "type": "keyDown",
      "target": "main",
      "key": "Tab"
    },
    {
      "type": "keyUp",
      "key": "Tab",
      "target": "main"
    },
    {
      "type": "change",
      "value": "jane@doe.com",
      "selectors": [
        [
          "#email"
        ]
      ],
      "target": "main"
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Promotion message"
        ],
        [
          "#promotion-label"
        ]
      ],
      "target": "main",
      "offsetX": 296.203125,
      "offsetY": 16.515625
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Submit"
        ],
        [
          "#submit-payment"
        ]
      ],
      "target": "main",
      "offsetX": 49.15625,
      "offsetY": 30.125
    },
    {
      "type": "click",
      "selectors": [
        [
          "aria/Thanks for your purchase. Please check your email for payment."
        ],
        [
          "#app > div.snackbar.success"
        ]
      ],
      "target": "main",
      "offsetX": 437,
      "offsetY": 65.1875
    }
  ]
}
