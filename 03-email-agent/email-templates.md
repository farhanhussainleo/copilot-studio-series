# Email Templates

This file contains the HTML email templates used for the static email tool in Episode 3.

## How to Use

When setting up the "Send all rooms email" tool in Copilot Studio:

1. Click **Tools** in the top bar of your agent
2. Click **Add a tool**
3. Find and select **Office 365 Outlook** connector
4. Click **Send an email (V2)**
5. Name the tool "Send all rooms email"
6. In the **Inputs** section under **Body**, select **Custom**
7. Copy and paste the template below into the custom field

---

## Complete Room Guide Template

Copy this entire template for the "Send all rooms email" tool:

```html
Hi there,<br><br>

Here's a complete guide to all Contoso conference rooms to help you make your decision:<br><br>

<strong>ROOM 1C - The Huddle</strong><br>
- Capacity: 6 people<br>
- Location: 1st Floor, Near Cafeteria<br>
- TV Size: 42" display<br>
- Best for: Small team meetings, 1-on-1s<br>
- Booking: Room-1C@contoso.com<br><br>

<strong>ROOM 2A - The Boardroom</strong><br>
- Capacity: 20 people<br>
- Location: 2nd Floor, West Wing<br>
- TV Size: 85" display<br>
- Best for: Executive meetings, presentations<br>
- Booking: Room-2A@contoso.com<br><br>

<strong>ROOM 3B - Innovation Lab</strong><br>
- Capacity: 12 people<br>
- Location: 3rd Floor, East Wing<br>
- TV Size: Dual 55" monitors<br>
- Best for: Brainstorming, design sprints<br>
- Booking: Room-3B@contoso.com<br><br>

<strong>ROOM 5A - The Arena</strong><br>
- Capacity: 50 people<br>
- Location: 5th Floor, Central<br>
- TV Size: 120" projector screen<br>
- Best for: All-hands meetings, large presentations<br>
- Booking: Room-5A@contoso.com<br><br>

<strong>How to Book:</strong><br>
1. Visit outlook.office.com<br>
2. Create a new meeting<br>
3. Add the room email as a required attendee<br>
4. The room will auto-accept if available<br><br>

Questions? Contact conference-rooms-demo@outlook.com<br><br>

Best,<br>
Conference Room Assistant
```

## Template Notes

- Uses HTML formatting (`<br>`, `<strong>`) for better readability
- Includes all room details from the knowledge source
- Provides clear booking instructions
- Professional signature from the agent
- Optimized for both desktop and mobile email clients