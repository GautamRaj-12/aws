# AWS Budgets: Protecting Your Wallet

## Introduction
- **Welcome Message:**
  - "Hi friends and welcome to the channel!"
- **Purpose:**
  - Introducing AWS Budgets to help control and monitor AWS spending.
  - Set a maximum budget and receive notifications to avoid overspending.

## Setting Up a Budget
- **Navigate to Budgets:**
  - Type "Budgets" in the AWS Management Console.
  - Must be logged in with your root account to access this feature.

### Creating a Budget
1. **Choose Budget Type:**
   - Cost, Usage, Savings Plans, or Reservations.
   - **Common Choice:** Cost budget.
2. **Name the Budget:**
   - Example: "Training Account $20 per month."
3. **Set Period:**
   - Options: Monthly, Daily, Quarterly, Annually.
   - Example: Monthly, with a recurring period starting this month.
4. **Set Amount:**
   - Fixed amount.
   - Example: $20.

### Filtering Options
- **Service-Specific Monitoring:**
  - Option to filter by specific services (e.g., EC2).
  - For simplicity, track all AWS services.

### Advanced Options
- **Aggregation and More:**
  - Optional advanced settings for specific needs.

## Setting Up Alerts
- **Alert Threshold:**
  - Example: 80% of the budget (i.e., $16).
  - Choose between actual costs or forecasted costs.
- **Notification Methods:**
  - Email (simple and effective).
  - Amazon SNS or Chatbot Alerts (advanced options).

## Optional Actions
- **Automated Actions:**
  - Example: Shutting down an EC2 instance if the budget is exceeded.
  - For simplicity, this step can be skipped.

### Review and Create
- **Review Settings:**
  - Ensure all details are correct.
- **Create Budget:**
  - Finalize and create your budget.

## Example Scenario
- **Previous Budgets:**
  - Example of a $10/month budget and a $20/month budget.
- **Over Budget Notification:**
  - Received an email notification upon exceeding the threshold.
  - Prompt action required to investigate and manage resources.

## Benefits of AWS Budgets
- **Quick and Free to Set Up:**
  - Essential for anyone using AWS for personal or business purposes.
- **Avoid Surprise Bills:**
  - Helps manage and control AWS spending effectively.

## Conclusion
- **Recommendation:**
  - Highly recommend setting up a budget to prevent unexpected costs.
- **Call to Action:**
  - If you found this helpful, give a thumbs up and consider subscribing for more content.