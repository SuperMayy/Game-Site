## Game Site
The timer should count down from the start date and will therefore need to automatically refresh its value every minute. **For the sake of the site the timer always "start" at 7 days regardless of the actual date or value of the tournament start date.**

The "join" button, refresh button, and both social media share buttons should be valid and accessible interactive elements. However **they do not route the user anywhere** (though the refresh button _should_ refetch data from the API as mentioned above).

### API Endpoint.

Endpoint:
`https://run.mocky.io/v3/e60fb51f-02b1-4ede-bd82-6c0481b5edda`

### Notes
- The **close button** at the top right of the design; is purely a visual placeholder.
- Some images are available via the API.
- Fully responsive;
- Make use of modern CSS layout techniques;
- Built from reusable UI components;
- Shows an understanding of both core React concepts such as `props` and modern development practices/techniques, such as `async/await` and React Hooks;
- Retrieves the necessary information from the provided API endpoint.
- Uses semantic code wherever possible, including HTML5 elements and human-readable variable naming;
- Is accessible for all users.

### Extras
- Uses [Jest] for unit testing (https://jestjs.io/) and [React Testing Library](https://testing-library.com/docs/react-testing-library/intro).

