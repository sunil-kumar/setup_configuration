# YMCA Content Hub

The Y Content Hub is a centralized digital platform where YMCA’s can share content with each other. It will also be a marketplace to validate approved vendors to share content.
- Y Content Hub is part of the Y Cloud ecosystem.
- Y Content Hub is FREE to use.
- Y Content Hub is all about our Collaboration and Community.
- Self-service Tools to contribute and consume content from Y Hub.
## Submodules

1. yhub_vy_registration - Virtual Y sites to register to Y Hub content sharing platform.
2. yhub_vy_videos - YMCA association contribute or consume video content to or from Y Hub.
3. yhub_vy_videos_api - Module provides Video API of Member flow
4. yhub_vy_videos_showcase - Module provides updated features for YMCA members.
5. yhub_vy_dashboard - Module provides video dashboard to show video metadata.

## Installation

**Prerequisites**

This assumes you've already [built an Virtual Y site](https://github.com/ymcatwincities/openy_gated_content#installation) and have it
 running.

- Add this module to your codebase.
  - via composer: `composer require yhub/ycontenthubextension`
  - without composer: this is not recommended.
- Enable the modules
   - Through the UI:
     - Visit **Extend** in your toolbar.
     - Check "Y Hub Registration" and "Y Hub Videos".
      - Install and say "yes" to add all required dependencies.
   - Via drush: `drush en yhub_vy_registration`
- Y Hub setting.
  - From the toolbar go to **Configuration** > **Web services** > **Y Hub** > **Y Hub Settings** and
  - Enter association site ID.
  - 'New video UI' checkbox should be checked.
  - Click on Save configuration to submit the settings. 
  
## Initial Features
- Any local Y can be a ‘contributor’ of the content.
- Any local Y can be a ‘consumer’ of the content.

## Y Hub new UI sections.
 **Virtual Y Videos listing page** section.
- From the toolbar go to **Virtual Y** > **Videos** > **Virtual Y Video**

 **Member flow page** section.
- 'https://www.association domain.com/yh-videos' 
- Example:'https://yusa-virtualy.y.org/yh-videos'


