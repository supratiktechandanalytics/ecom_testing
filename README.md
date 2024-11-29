**Test Plan for OpenCart Website**

**1. Introduction**
This test plan defines the testing strategy, scope, and objectives for manual testing of the OpenCart website. OpenCart is an open-source e-commerce platform that provides features for user management, product browsing, cart functionality, and checkout processes.

**2. Objectives**
Verify the core functionality of OpenCart's features, such as product browsing, adding/removing items from the cart, checkout, and order placement.
Validate the UI/UX for design consistency, responsiveness, and user experience.
Test cross-browser and cross-device compatibility.
Identify bugs and issues to ensure quality.

**3. Scope of Testing**
Functional Testing: Core functionalities like user registration, login, product catalog, and cart management.
UI/UX Testing: Ensuring intuitive and responsive design across different devices.
Cross-Browser Testing: Compatibility on various browsers (Chrome, Firefox, Edge, Safari, etc.).
Performance Testing: Validate page load times and responsiveness.
Regression Testing: Test existing functionalities after bug fixes.

**4. Test Approach**
Perform manual testing by simulating user scenarios on OpenCart's platform.
Document issues systematically using a standard bug reporting template.
Retest resolved issues to ensure they don’t introduce new bugs.

**5. Test Environment**
Browsers: Chrome, Firefox, Edge, Safari.
Devices: Android, iOS, Windows, macOS.
Tools: BrowserStack or local devices for cross-browser/device testing.
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>Functional Test Cases</h2>
    <table>
        <thead>
            <tr>
                <th>Test Case ID</th>
                <th>Test Scenario</th>
                <th>Test Steps</th>
                <th>Expected Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>TC01</td>
                <td>Verify login with valid credentials</td>
                <td>
                    1. Open the OpenCart admin login page.<br>
                    2. Enter valid username and password.<br>
                    3. Click "Login".
                </td>
                <td>Admin dashboard should be displayed successfully.</td>
            </tr>
            <tr>
                <td>TC02</td>
                <td>Verify adding a product</td>
                <td>
                    1. Log in to the admin panel.<br>
                    2. Navigate to "Catalog > Products".<br>
                    3. Click "Add New" and fill in all required fields.<br>
                    4. Save the product.
                </td>
                <td>Product should be added successfully and visible in the product list.</td>
            </tr>
            <tr>
                <td>TC03</td>
                <td>Verify checkout process</td>
                <td>
                    1. Add items to the cart as a customer.<br>
                    2. Proceed to checkout.<br>
                    3. Fill in the billing and shipping information.<br>
                    4. Place the order.
                </td>
                <td>Order should be placed successfully with a confirmation message.</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>UI/UX Test Cases</h2>
    <table>
        <thead>
            <tr>
                <th>Test Case ID</th>
                <th>Test Scenario</th>
                <th>Test Steps</th>
                <th>Expected Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>TC04</td>
                <td>Verify responsiveness of the homepage</td>
                <td>
                    1. Open the homepage on desktop, tablet, and mobile devices.
                </td>
                <td>Homepage layout should adjust seamlessly across different devices.</td>
            </tr>
            <tr>
                <td>TC05</td>
                <td>Verify alignment of buttons and labels</td>
                <td>
                    1. Open any product or checkout page.<br>
                    2. Check the alignment of buttons, text labels, and input fields.
                </td>
                <td>All elements should be properly aligned without overlapping or misplacement.</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>Cross-Browser Test Cases</h2>
    <table>
        <thead>
            <tr>
                <th>Test Case ID</th>
                <th>Test Scenario</th>
                <th>Test Steps</th>
                <th>Expected Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>TC06</td>
                <td>Verify compatibility on Google Chrome</td>
                <td>
                    1. Open OpenCart on Chrome.<br>
                    2. Browse different modules like catalog and checkout.
                </td>
                <td>Website should function properly on Chrome without issues.</td>
            </tr>
            <tr>
                <td>TC07</td>
                <td>Verify compatibility on Microsoft Edge</td>
                <td>
                    1. Open OpenCart on Edge.<br>
                    2. Browse different modules like catalog and checkout.
                </td>
                <td>Website should function properly on Edge without issues.</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>Bug Report</h2>
    <table>
        <thead>
            <tr>
                <th>Field</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Bug ID</td>
                <td>BUG001</td>
            </tr>
            <tr>
                <td>Module/Feature</td>
                <td>Product Search</td>
            </tr>
            <tr>
                <td>Severity</td>
                <td>Medium</td>
            </tr>
            <tr>
                <td>Priority</td>
                <td>High</td>
            </tr>
            <tr>
                <td>Summary</td>
                <td>Search results do not display correct products.</td>
            </tr>
            <tr>
                <td>Steps to Reproduce</td>
                <td>
                    1. Navigate to the product search bar.<br>
                    2. Enter a product keyword and click "Search".<br>
                    3. Observe the results.
                </td>
            </tr>
            <tr>
                <td>Expected Result</td>
                <td>Search results should display relevant products based on the keyword.</td>
            </tr>
            <tr>
                <td>Actual Result</td>
                <td>Irrelevant or no results are displayed.</td>
            </tr>
            <tr>
                <td>Attachments</td>
                <td>Screenshot of the search result issue is attached.</td>
            </tr>
            <tr>
                <td>Reported By</td>
                <td>Supratik Sarkar</td>
            </tr>
            <tr>
                <td>Date</td>
                <td>29-Nov-2024</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
