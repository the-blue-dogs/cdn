# Blue Dogs CDN

This repository serves as a Content Delivery Network (CDN) for the Blue Dogs, designed to organize and deliver public assets. It enables content access within VRChat worlds while providing reliable static file hosting.

## Folder Structure

-   **internal/**

    -   Contains internal-use files/backups not meant for public distribution (things that aren't currently being used).
    -   Keeps the public assets clean.
    -   Example: `AdSlotC.jpg` (ad slot available image that's currently not in use)

-   **public/**
    -   Contains all files intended for public access.
    -   Organized into subfolders:
        -   **docs/**
            -   General Documentation and guidelines for users (or advertisers).
            -   Example: `AdvertGuidelines.pdf`
        -   **images/**
            -   Publicly available images (mostly for use in worlds).
            -   Examples: `AdSlotA.jpg`, `AdSlotB.jpg`, `AdSlot[X].jpg`, `CommunityBoard.jpg`, `EventPoster.jpg`
        -   **misc/**
            -   Miscellaneous public files.
            -   Example: `SpinTheWheelPrompts.txt`

## Usage

### Adding a new advertisement

1.  Move the "Slot Available" image in `public/images/` to the `internal/` folder.
2.  Place the advertisement image in the `public/images/` folder. (Make sure it is named exactly `AdSlotX.jpg`, replacing `X` with the appropriate letter.)

### Removing an advertisement

1.  Delete the advertisement image from the `public/images/` folder.
2.  Move the appropriate "Slot Available" image from the `internal/` folder back to the `public/images/` folder.

### Updating a file

> This is only for updating existing advertisements, posters, boards, etc. Do not use this when adding a new advertiser into a slot.

1.  Delete the file in the appropriate `public/<folder>/`.
2.  Place the updated file in the `public/<folder>/` folder. (Make sure it is exactly as it was previously)

#### Example

1. Delete `EventPoster.jpg` from `public/images/`.
2. Place the updated image in the `public/images/` folder.
3. Ensure it is named `EventPoster.jpg`.
4. Stage, Commit, and Push the changes.
