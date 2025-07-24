---  
order: 1000  
label: Config File  
icon: rocket  
---

# Config.js

The `config.js` file is the core configuration of your website — it defines key details that personalize and set up your site's appearance and information.

This file allows you to customize:

- **Site Title**
- **Icon (Profile Picture)**
- **Description/About Me**
- **Social Media Links**
- **Footer Content**

## Example Configuration

Below is a **complete** sample of the `config.js` file. Feel free to copy, customize, and adapt it to your needs:

```js
// Profile Configuration
const CONFIG = {
	// Basic Profile Information
	profile: {
		image: "YOUR_ICON_URL",
		name: "Your Name",
		description: "A Little Description About You",

		footer: "Footer Content"
	},

	// Social Media Links
	socials: {
		// Popular Development Platforms
		github: {
			enabled: true,
			url: "https://github.com/your-username",
			title: "GitHub"
		},
		gitlab: {
			enabled: true,
			url: "https://gitlab.com/your-username",
			title: "GitLab"
		},
		bitbucket: {
			enabled: true,
			url: "https://bitbucket.org/your-username",
			title: "Bitbucket"
		},
		codepen: {
			enabled: true,
			url: "https://codepen.io/your-username",
			title: "CodePen"
		},
		replit: {
			enabled: false,
			url: "https://replit.com/@your-username",
			title: "Replit"
		},
		stackoverflow: {
			enabled: false,
			url: "https://stackoverflow.com/users/your-username",
			title: "Stack Overflow"
		},

		// Communication Platforms
		discord: {
			enabled: true,
			url: "https://discord.com/users/your-user-id",
			title: "Discord"
		},
		email: {
			enabled: true,
			url: "mailto:YOUR_EMAIL",
			title: "Email"
		},
		telegram: {
			enabled: false,
			url: "https://t.me/your-username",
			title: "Telegram"
		},
		whatsapp: {
			enabled: false,
			url: "https://wa.me/your-whatsapp-phone-number",
			title: "WhatsApp"
		},
		signal: {
			enabled: false,
			url: "https://signal.me/#p/+your-phone-number",
			title: "Signal"
		},
		skype: {
			enabled: false,
			url: "skype:YOUR_SKYPE_USERNAME?chat",
			title: "Skype"
		},

		// Social Media Platforms
		reddit: {
			enabled: false,
			url: "https://reddit.com/user/your-username/",
			title: "Reddit"
		},
		twitter: {
			enabled: false,
			url: "https://twitter.com/your-username",
			title: "Twitter"
		},
		facebook: {
			enabled: false,
			url: "https://facebook.com/your-username",
			title: "Facebook"
		},
		instagram: {
			enabled: false,
			url: "https://instagram.com/your-username",
			title: "Instagram"
		},
		tiktok: {
			enabled: false,
			url: "https://tiktok.com/@your-username",
			title: "TikTok"
		},
		snapchat: {
			enabled: false,
			url: "https://snapchat.com/add/your-username",
			title: "Snapchat"
		},
		mastodon: {
			enabled: false,
			url: "https://mastodon.social/@your-username",
			title: "Mastodon"
		},
		bluesky: {
			enabled: false,
			url: "https://bsky.app/profile/your-bluesky-handle",
			title: "Bluesky"
		},
		threads: {
			enabled: false,
			url: "https://threads.net/@your-username",
			title: "Threads"
		},

		// Professional Networks
		linkedin: {
			enabled: true,
			url: "https://linkedin.com/in/your-username",
			title: "LinkedIn"
		},
		behance: {
			enabled: false,
			url: "https://behance.net/your-username",
			title: "Behance"
		},
		dribbble: {
			enabled: false,
			url: "https://dribbble.com/your-username",
			title: "Dribbble"
		},
		upwork: {
			enabled: false,
			url: "https://upwork.com/freelancers/your-username",
			title: "Upwork"
		},
		fiverr: {
			enabled: false,
			url: "https://fiverr.com/your-username",
			title: "Fiverr"
		},

		// Content Creation Platforms
		youtube: {
			enabled: false,
			url: "https://youtube.com/@your-channel",
			title: "YouTube"
		},
		twitch: {
			enabled: false,
			url: "https://twitch.tv/your-username",
			title: "Twitch"
		},
		medium: {
			enabled: false,
			url: "https://medium.com/@your-username",
			title: "Medium"
		},
		devto: {
			enabled: false,
			url: "https://dev.to/your-username", // 
			title: "Dev.to"
		},
		hashnode: {
			enabled: false,
			url: "https://hashnode.com/@your-username",
			title: "Hashnode"
		},
		substack: {
			enabled: false,
			url: "https://your-username.substack.com",
			title: "Substack"
		},

		// Gaming Platforms
		steam: {
			enabled: false,
			url: "https://steamcommunity.com/id/your-username",
			title: "Steam"
		},
		epicgames: {
			enabled: false,
			url: "https://store.epicgames.com/u/your-username",
			title: "Epic Games"
		},
		xbox: {
			enabled: false,
			url: "https://account.xbox.com/profile?gamertag=your-username",
			title: "Xbox Live"
		},
		playstation: {
			enabled: false,
			url: "https://psnprofiles.com/your-username",
			title: "PlayStation"
		},

		// Music Platforms
		spotify: {
			enabled: false,
			url: "https://open.spotify.com/user/your-username",
			title: "Spotify"
		},
		soundcloud: {
			enabled: false,
			url: "https://soundcloud.com/your-username",
			title: "SoundCloud"
		},
		applemusic: {
			enabled: false,
			url: "https://music.apple.com/profile/your-username",
			title: "Apple Music"
		},
		bandcamp: {
			enabled: false,
			url: "https://your-username.bandcamp.com",
			title: "Bandcamp"
		},

		// Other Platforms
		pinterest: {
			enabled: false,
			url: "https://pinterest.com/your-username",
			title: "Pinterest"
		},
		tumblr: {
			enabled: false,
			url: "https://your-username.tumblr.com",
			title: "Tumblr"
		},
		flickr: {
			enabled: false,
			url: "https://flickr.com/people/your-username",
			title: "Flickr"
		},
		vimeo: {
			enabled: false,
			url: "https://vimeo.com/your-username",
			title: "Vimeo"
		},
		patreon: {
			enabled: false,
			url: "https://patreon.com/your-username",
			title: "Patreon"
		},
		kofi: {
			enabled: false,
			url: "https://ko-fi.com/your-username",
			title: "Ko-fi"
		},
		buymeacoffee: {
			enabled: false,
			url: "https://buymeacoffee.com/your-username",
			title: "Buy Me a Coffee"
		},

		// Personal Website/Portfolio
		website: {
			enabled: true,
			url: "https://example.com/",
			title: "Website"
		}
	}
};
```

## How to Set Up Your Configuration

1. **Profile Image:** Replace the placeholder URL with your profile picture URL.
2. **Name & About Me:** Modify the `name` and `description` fields.
3. **Social Media:** Enable or disable social links and update their URLs.
4. **Footer:** Customize your footer message.

### Important

- Only enable social links you want visible.
- Keep URLs accurate.
- Save this as `config.js` in your project directory.

## Support

If you require assistance. Feel free to open an issue or the discussion in our [**GitHub repository**](https://github.com/profilie/profilie/).

