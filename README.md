# aWATTar

aWATTar provides a free, public REST API delivering real-time and next-day hourly electricity spot prices sourced from the EPEX Spot market exchange for both Austria and Germany. The API enables developers, smart home integrators, and commercial operators to build dynamic energy pricing applications that respond to market conditions. Prices are updated daily at 14:00 CET covering the following day, and the API returns JSON data including start/end timestamps and market price per MWh. No authentication token is required, making integration straightforward for any developer.

**API Endpoints:**
- Austria: `https://api.awattar.at/v1/marketdata`
- Germany: `https://api.awattar.de/v1/marketdata`

**Rate Limit:** 100 requests per day (fair-use, IP-based, no token required)

**Links:**
- Website: https://www.awattar.at
- API Documentation: https://www.awattar.at/services/api
- GitHub Org: https://github.com/awattarenergy
- LinkedIn: https://www.linkedin.com/company/awattar
- Blog: https://www.awattar.at/blog
- Support: https://support.awattar.at

**Maintained by:** Kin Lane (kin@apievangelist.com)
