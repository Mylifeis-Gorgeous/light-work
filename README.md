"# light-work" 
isssue
imbalanced on mobile phone

root-cause
The issue you're experiencing is likely due to how responsive design works. When you set a left margin of 30% and a right margin of 30% on desktop, it looks balanced because the screen width is wide enough to accommodate those margins. However, on a smartphone, the screen is much narrower, and the same margins can create an imbalance.

solution
Media Queries: Use CSS media queries to adjust the margins for smaller screens. For example, you can set smaller margins or remove them altogether for mobile devices.
