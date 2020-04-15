{
  "id": "7f98ca4d-2a63-4105-9d7d-62e09c100016",
  "version": "2.0",
  "name": "Test_1",
  "url": "https://www.google.com",
  "tests": [{
    "id": "eecad020-9c61-400a-814f-007c2401156e",
    "name": "VideoGame",
    "commands": [{
      "id": "c4d739ef-6127-4815-b9c9-76da3641142b",
      "comment": "",
      "command": "open",
      "target": "/",
      "targets": [],
      "value": ""
    }, {
      "id": "860cff72-d4da-4a1b-86a0-422ca6188f6e",
      "comment": "",
      "command": "setWindowSize",
      "target": "825x990",
      "targets": [],
      "value": ""
    }, {
      "id": "5f4bd5fe-0b65-4608-93ed-8d99eb15bab5",
      "comment": "",
      "command": "click",
      "target": "name=q",
      "targets": [
        ["name=q", "name"],
        ["css=.gLFyf", "css:finder"],
        ["xpath=//input[@name='q']", "xpath:attributes"],
        ["xpath=//form[@id='tsf']/div[2]/div/div/div/div[2]/input", "xpath:idRelative"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "3fc696e2-7900-4de6-8973-9212185345f0",
      "comment": "",
      "command": "type",
      "target": "name=q",
      "targets": [
        ["name=q", "name"],
        ["css=.gLFyf", "css:finder"],
        ["xpath=//input[@name='q']", "xpath:attributes"],
        ["xpath=//form[@id='tsf']/div[2]/div/div/div/div[2]/input", "xpath:idRelative"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "how to become a programmer"
    }, {
      "id": "1ae92180-ec9a-4f11-aeec-916062ddf873",
      "comment": "",
      "command": "sendKeys",
      "target": "name=q",
      "targets": [
        ["name=q", "name"],
        ["css=.gLFyf", "css:finder"],
        ["xpath=//input[@name='q']", "xpath:attributes"],
        ["xpath=//form[@id='tsf']/div[2]/div/div/div/div[2]/input", "xpath:idRelative"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "${KEY_ENTER}"
    }, {
      "id": "2219a2d0-14ab-496f-8e65-c7de5b5b9ec5",
      "comment": "",
      "command": "click",
      "target": "css=.g:nth-child(11) .LC20lb",
      "targets": [
        ["css=.g:nth-child(11) .LC20lb", "css:finder"],
        ["xpath=//div[@id='rso']/div[7]/div/div/a/h3", "xpath:idRelative"],
        ["xpath=//div[7]/div/div/a/h3", "xpath:position"],
        ["xpath=//h3[contains(.,'How To Become A Programmer (The 3 Best Ways)')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "744efdef-2676-45e0-a5a2-49878841324e",
      "comment": "",
      "command": "mouseOver",
      "target": "id=logo",
      "targets": [
        ["id=logo", "id"],
        ["css=#logo", "css:finder"],
        ["xpath=//a[@id='logo']", "xpath:attributes"],
        ["xpath=//a[contains(@href, 'https://simpleprogrammer.com/')]", "xpath:href"],
        ["xpath=//a", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f9cb72ac-ca35-4f67-8778-5575f3ce0a48",
      "comment": "",
      "command": "mouseOut",
      "target": "id=logo",
      "targets": [
        ["id=logo", "id"],
        ["css=#logo", "css:finder"],
        ["xpath=//a[@id='logo']", "xpath:attributes"],
        ["xpath=//a[contains(@href, 'https://simpleprogrammer.com/')]", "xpath:href"],
        ["xpath=//a", "xpath:position"]
      ],
      "value": ""
    }]
  }],
  "suites": [{
    "id": "0a59ec0e-6c2f-4222-96df-fca4789fd3d1",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": ["eecad020-9c61-400a-814f-007c2401156e"]
  }],
  "urls": ["https://www.google.com/"],
  "plugins": []
}
