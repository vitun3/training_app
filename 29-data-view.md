# 9. Data View

## Main Entities
- User
- TrainingPlan
- WorkoutSession
- Exercise
- SocialPost
- FollowRelation
- Notification

## Relationships
- A user owns multiple training plans and workout sessions.
- A workout session belongs to a plan or can be standalone.
- A social post is authored by a user and may reference a workout or plan.
- Notifications are produced from user actions and delivered to recipients.

## Storage Approach
- Use a relational database for transactional consistency.
- Keep media files in object storage.
- Use caching for frequently read social and dashboard data.
