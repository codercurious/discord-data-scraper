### Important points to consider when using this actor
1. You can save costs by configuring this actor to run on low memory, as low as 512MB. Increasing memory won't make it faster or better.
2. If the actor stops before scraping all records due to unexpected error, you can simply ressurect the actor to resume scraping.

### How to get Token
Go to discord web app, login to your account
Open Developer tools (3 Dots Menu > More tools > Developer tools)
Goto 'Console' Tab and paste following code and press ENTER. It will copy the token to your clipboard automatically. 
You should get message that says "Worked!" if the token was copied successfully.
```js
window.webpackChunkdiscord_app.push([
  [Math.random()],
  {},
  req => {
    for (const m of Object.keys(req.c)
      .map(x => req.c[x].exports)
      .filter(x => x)) {
      if (m.default && m.default.getToken !== undefined) {
        return copy(m.default.getToken());
      }
      if (m.getToken !== undefined) {
        return copy(m.getToken());
      }
    }
  },
]);
console.log('%cWorked!', 'font-size: 50px');
console.log(`%cYou now have your token in the clipboard!`, 'font-size: 16px');
```


Here is the sample output of this actor:

```json
{
	"id": "1131713979111186482",
	"type": 19,
	"content": "**high definition photo of a modern powder bathroom in a high-end home in the desert. bright daytime light and a skylight. white oak and natural materials and woven textures with desert inspirted colors, modern desert-inspired spanish tile. Matte black hardware. Modern light sconces around the vanity mirror. Include some natural desert elements into the design. (fast)** - Image #2 <@1122599062454157382>",
	"channel_id": "1008571020480876554",
	"author": {
		"id": "936929561302675456",
		"username": "Midjourney Bot",
		"avatar": "f6ce562a6b4979c4b1cbc5b436d3be76",
		"discriminator": "9282",
		"public_flags": 589824,
		"flags": 589824,
		"bot": true,
		"banner": null,
		"accent_color": null,
		"global_name": null,
		"avatar_decoration": null,
		"display_name": null,
		"banner_color": null
	},
	"attachments": [
		{
			"id": "1131713978821791776",
			"filename": "camcooke_high_definition_photo_of_a_modern_powder_bathroom_in_a_f58fa448-1620-4aca-9621-005ef9f3b383.png",
			"size": 1433631,
			"url": "https://cdn.discordapp.com/attachments/1008571020480876554/1131713978821791776/camcooke_high_definition_photo_of_a_modern_powder_bathroom_in_a_f58fa448-1620-4aca-9621-005ef9f3b383.png",
			"proxy_url": "https://media.discordapp.net/attachments/1008571020480876554/1131713978821791776/camcooke_high_definition_photo_of_a_modern_powder_bathroom_in_a_f58fa448-1620-4aca-9621-005ef9f3b383.png",
			"width": 1024,
			"height": 1024,
			"content_type": "image/png"
		}
	],
	"embeds": [],
	"mentions": [
		{
			"id": "1122599062454157382",
			"username": "camcooke",
			"avatar": null,
			"discriminator": "0",
			"public_flags": 0,
			"flags": 0,
			"banner": null,
			"accent_color": null,
			"global_name": "camcam",
			"avatar_decoration": null,
			"display_name": "camcam",
			"banner_color": null
		}
	],
	"mention_roles": [],
	"pinned": false,
	"mention_everyone": false,
	"tts": false,
	"timestamp": "2023-07-20T22:27:18.849000+00:00",
	"edited_timestamp": null,
	"flags": 0,
	"components": [
		{
			"type": 1,
			"components": [
				{
					"type": 2,
					"custom_id": "MJ::JOB::high_variation::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"label": "Vary (Strong)",
					"emoji": {
						"name": "🪄"
					}
				},
				{
					"type": 2,
					"custom_id": "MJ::JOB::low_variation::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"label": "Vary (Subtle)",
					"emoji": {
						"name": "🪄"
					}
				}
			]
		},
		{
			"type": 1,
			"components": [
				{
					"type": 2,
					"custom_id": "MJ::Outpaint::50::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"label": "Zoom Out 2x",
					"emoji": {
						"name": "🔍"
					}
				},
				{
					"type": 2,
					"custom_id": "MJ::Outpaint::75::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"label": "Zoom Out 1.5x",
					"emoji": {
						"name": "🔍"
					}
				},
				{
					"type": 2,
					"custom_id": "MJ::CustomZoom::f58fa448-1620-4aca-9621-005ef9f3b383",
					"style": 2,
					"label": "Custom Zoom",
					"emoji": {
						"name": "🔍"
					}
				}
			]
		},
		{
			"type": 1,
			"components": [
				{
					"type": 2,
					"custom_id": "MJ::JOB::pan_left::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"emoji": {
						"name": "⬅️"
					}
				},
				{
					"type": 2,
					"custom_id": "MJ::JOB::pan_right::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"emoji": {
						"name": "➡️"
					}
				},
				{
					"type": 2,
					"custom_id": "MJ::JOB::pan_up::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"emoji": {
						"name": "⬆️"
					}
				},
				{
					"type": 2,
					"custom_id": "MJ::JOB::pan_down::1::f58fa448-1620-4aca-9621-005ef9f3b383::SOLO",
					"style": 2,
					"emoji": {
						"name": "⬇️"
					}
				}
			]
		},
		{
			"type": 1,
			"components": [
				{
					"type": 2,
					"custom_id": "MJ::BOOKMARK::f58fa448-1620-4aca-9621-005ef9f3b383",
					"style": 2,
					"emoji": {
						"name": "❤️"
					}
				},
				{
					"type": 2,
					"style": 5,
					"label": "Web",
					"url": "https://www.midjourney.com/app/jobs/f58fa448-1620-4aca-9621-005ef9f3b383/"
				}
			]
		}
	],
	"message_reference": {
		"channel_id": "1008571020480876554",
		"message_id": "1131713804179362064",
		"guild_id": "662267976984297473"
	},
	"referenced_message": {
		"id": "1131713804179362064",
		"type": 19,
		"content": "**high definition photo of a modern powder bathroom in a high-end home in the desert. bright daytime light and a skylight. white oak and natural materials and woven textures with desert inspirted colors, modern desert-inspired spanish tile. Matte black hardware. Modern light sconces around the vanity mirror. Include some natural desert elements into the design. (fast)** - Variations (Strong) by <@1122599062454157382> (fast)",
		"channel_id": "1008571020480876554",
		"author": {
			"id": "936929561302675456",
			"username": "Midjourney Bot",
			"avatar": "f6ce562a6b4979c4b1cbc5b436d3be76",
			"discriminator": "9282",
			"public_flags": 589824,
			"flags": 589824,
			"bot": true,
			"banner": null,
			"accent_color": null,
			"global_name": null,
			"avatar_decoration": null,
			"display_name": null,
			"banner_color": null
		},
		"attachments": [
			{
				"id": "1131713803940274198",
				"filename": "camcooke_high_definition_photo_of_a_modern_powder_bathroom_in_a_3eaa7c0c-9825-4110-9c89-02c4e463a8d0.png",
				"size": 6647039,
				"url": "https://cdn.discordapp.com/attachments/1008571020480876554/1131713803940274198/camcooke_high_definition_photo_of_a_modern_powder_bathroom_in_a_3eaa7c0c-9825-4110-9c89-02c4e463a8d0.png",
				"proxy_url": "https://media.discordapp.net/attachments/1008571020480876554/1131713803940274198/camcooke_high_definition_photo_of_a_modern_powder_bathroom_in_a_3eaa7c0c-9825-4110-9c89-02c4e463a8d0.png",
				"width": 2048,
				"height": 2048,
				"content_type": "image/png"
			}
		],
		"embeds": [],
		"mentions": [
			{
				"id": "1122599062454157382",
				"username": "camcooke",
				"avatar": null,
				"discriminator": "0",
				"public_flags": 0,
				"flags": 0,
				"banner": null,
				"accent_color": null,
				"global_name": "camcam",
				"avatar_decoration": null,
				"display_name": "camcam",
				"banner_color": null
			}
		],
		"mention_roles": [],
		"pinned": false,
		"mention_everyone": false,
		"tts": false,
		"timestamp": "2023-07-20T22:26:37.142000+00:00",
		"edited_timestamp": null,
		"flags": 0,
		"components": [
			{
				"type": 1,
				"components": [
					{
						"type": 2,
						"custom_id": "MJ::JOB::upsample::1::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 1,
						"label": "U1"
					},
					{
						"type": 2,
						"custom_id": "MJ::JOB::upsample::2::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 1,
						"label": "U2"
					},
					{
						"type": 2,
						"custom_id": "MJ::JOB::upsample::3::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 1,
						"label": "U3"
					},
					{
						"type": 2,
						"custom_id": "MJ::JOB::upsample::4::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 1,
						"label": "U4"
					},
					{
						"type": 2,
						"custom_id": "MJ::JOB::reroll::0::3eaa7c0c-9825-4110-9c89-02c4e463a8d0::SOLO",
						"style": 2,
						"emoji": {
							"name": "🔄"
						}
					}
				]
			},
			{
				"type": 1,
				"components": [
					{
						"type": 2,
						"custom_id": "MJ::JOB::variation::1::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 2,
						"label": "V1"
					},
					{
						"type": 2,
						"custom_id": "MJ::JOB::variation::2::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 2,
						"label": "V2"
					},
					{
						"type": 2,
						"custom_id": "MJ::JOB::variation::3::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 2,
						"label": "V3"
					},
					{
						"type": 2,
						"custom_id": "MJ::JOB::variation::4::3eaa7c0c-9825-4110-9c89-02c4e463a8d0",
						"style": 2,
						"label": "V4"
					}
				]
			}
		],
		"message_reference": {
			"channel_id": "1008571020480876554",
			"message_id": "1131713484078461018",
			"guild_id": "662267976984297473"
		}
	}
}
```
