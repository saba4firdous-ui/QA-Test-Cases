# Login Test Scenarios

## Functional

1. Verify login with valid username and valid password.
2. Verify successful navigation to the home page after login.
3. Verify user remains on the login page after failed login.
4. Verify login button functionality when clicked once.
5. Verify login is triggered when the Enter key is pressed.

## Validation

6. Verify login with valid username and invalid password.
7. Verify login with invalid username and valid password.
8. Verify login with invalid username and invalid password.
9. Verify login with blank username and valid password.
10. Verify login with valid username and blank password.
11. Verify login with both username and password left blank.
12. Verify login when username contains only numeric characters.
13. Verify login when username contains special characters.
14. Verify login when username contains alphanumeric characters.
15. Verify login when username contains leading spaces.
16. Verify login when username contains trailing spaces.
17. Verify login when password contains leading spaces.
18. Verify login when password contains trailing spaces.
19. Verify login when username contains spaces between characters.
20. Verify login with username having different letter casing.
21. Verify password field is case-sensitive.

## Boundary Testing

22. Verify login when username exceeds the maximum allowed length.
23. Verify login when password exceeds the maximum allowed length.
24. Verify login with a single-character username.
25. Verify login with a single-character password.
26. Verify login using very long input values.

## Negative Testing

27. Verify login when only spaces are entered in both fields.

## Navigation

28. Verify Forgot Password link redirects to Forgot Password page.
29. Verify user is redirected to Login page after logout.

## UI Testing

30. Verify Username field is visible.
31. Verify Password field is visible.
32. Verify Login button is visible.
33. Verify Forgot Password link is visible.
34. Verify field labels are displayed correctly.

## Error Handling

35. Verify correct error message is displayed for invalid credentials.
36. Verify correct error message is displayed when username and password are blank.
37. Verify error message disappears after successful login.
38. Verify error message formatting and visibility.

## Security Testing

39. Verify password field masks entered characters.
40. Verify password is not visible after page refresh.
41. Verify user cannot access protected pages without login.
42. Verify user session is created only after successful login.
43. Verify user is logged out after clicking Logout.

## Session Testing

44. Verify logged-in session remains active after page refresh.
45. Verify user remains logged in when navigating between pages.
46. Verify application behavior when the browser is refreshed before login.
47. Verify application behavior when the browser Back button is used after login.
48. Verify user session expires after the configured inactivity period.

## Error Guessing

49. Verify login behavior when Login button is clicked multiple times rapidly.

