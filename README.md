# Completed Auctions Data Repository

This repository contains automatically exported completed auction data from the Zed Champions database.

## Data Updates

- **Last Updated**: 2025-06-30 19:47:12 UTC
- **Update Frequency**: Real-time (updated immediately when new auctions are imported)
- **Data Source**: Zed Champions Database

## File Organization

Files are organized by the actual UTC date that auctions ended:
- `completed_auctions_YYYY-MM-DD.csv` - All auctions that ended on this specific UTC date

Each file contains all auctions that ended on that particular date, sorted by end time.

## Data Fields

| Field | Description |
|-------|-------------|
| listing_id | Unique auction identifier |
| end_time | When the auction ended (UTC) |
| settle_time | When the auction was settled (UTC) |
| listing_type | Type of auction (e.g., STUD_AUCTION) |
| listing_state | State of auction (COMPLETE) |
| horse_id | Unique horse identifier |
| horse_name | Name of the horse |
| horse_gender | Horse gender |
| hex_color | Horse color code |
| generation | Horse generation number |
| bloodline | Horse bloodline (SZABO, NAKAMOTO, etc.) |
| complete_rating | Overall horse rating |
| breeding_slots | Number of breeding slots |
| winning_bid_amount | Final winning bid amount |
| winning_bidder | Name of winning bidder |
| total_bids | Total number of bids |
| user_id | User ID of auction creator |

## Access

This data is automatically updated and can be accessed via:
- Direct file download from this repository
- GitHub API
- Git clone: `git clone https://github.com/myblood-tempest/completed-auctions.git`

## Contact

For questions about this data, contact the repository owner.
