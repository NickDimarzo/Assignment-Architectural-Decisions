# Architecture Decision Record: Native, Web or Hybrid

Contents:

- Summary
    - Issue
    - Decision
    - Status
- Details
    - Assumptions
    - Constraints
    - Positions
    - Argument
    - Implications
- Related
    - Related decisions
    - Related requirements
    - Related artifacts
    - Related principles
- Notes

## Summary
This ADR aims to determine whether the mobile application for the retail company should be developed as a native, web, or hybrid app, considering various factors such as offline support, push notifications, payment gateways, analytics, image storage, and internationalization requirements.

### Issue
The development team needs to decide on the most suitable app architecture to meet the retail company's requirements

### Decision
The team has decided to develop a hybrid application

### Status
Accepted

## Details

### Assumptions
1. The target audience uses primarily uses iOS and Android devices
2. The hybrid app development framework is able to meet the app's requirements
3. The development team has the required expertise and resources to develop and maintain the app

### Constraints
1. Performance: Hybrid apps have performance overhead compared to fully native app's.
2. User Experience: Hybrid app's may struggle to provide the same level of user experience as fully native apps.
3. Access to Device Features: Hybrid apps rely on plugins or APIs to access device feature.

### Positions
1. Native App: Provides optimal performance and user experience but requires separate development efforts for each platform.

2. Web App: Offers cross-platform compatibility and easier maintenance but lacks certain native functionality.

3. Hybrid App: Combines benefits of both native and web apps, allowing for code reuse and leveraging platform-specific features through plugins.

### Argument
Developing the app as a hybrid app aligns with the retail company's requirements and constraints. It provides a cross-platform solution by leveraging code reuse across operating systems and allows for the integration of native functionality through plugins. 

### Implications
1. Reduced development time and cost compared to developing separate native apps for iOS and Android.

2. App performance may not match that of a fully native app, although it can be optimized to provide a native-like experience.

3. The team will need to select a suitable hybrid app development framework and ensure proper integration with the required plugins.

## Related

### Related Decisions
None

### Related Requirements
Offline mode support, push notifications, payment gateway integration, analytics, internationalization, image storage optimization.

### Related Artifacts
None

### Related Principles
cross-platform compatibility, native-like user experience.

## Notes
Consider conducting a proof of concept or prototype to validate the chosen hybrid app development framework's capabilities and performance before proceeding with full-scale development. Regular performance testing and optimization should be performed to ensure the app meets the desired performance standards.

