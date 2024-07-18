<div class="container">
  <div class="card">
    <div class="profile">
      <img src="profile-thumbnail.png" alt="card profile" />
      <div class="profile-info">
        <span class="neutral-900">Sarah Dole</span>
        <span class="neutral-600">@sarahdole</span>
      </div>
    </div>
    <p class="neutral-600">
      I've been searching for high-quality abstract images for my design projects, and I'm thrilled to have found this platform. The variety
      and depth of creativity are astounding!
    </p>
  </div>
</div>

<style>
  .container {
    padding-top: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .card {
    background: white;
    border: 1px solid #e6e6e6;
    width: 342px;
    height: 233px;
    padding: 24px;
    border-radius: 8px;
    box-shadow:
      0 1px 3px rgba(0, 0, 0, 0.1),
      0 1px 2px rgba(0, 0, 0, 0.06);
  }

  .profile {
    display: flex;
    align-items: center;
    margin-bottom: 16px;
  }

  .profile-info {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .profile-info span:first-of-type {
    font-weight: 600;
    font-size: 18px;
    margin-bottom: 1px;
  }

  .profile-info span:last-of-type {
    font-size: 14px;
  }

  .profile img {
    width: 48px;
    height: 48px;
    border-radius: 50%;
    margin-right: 16px;
  }

  p {
    font-size: 16px;
    line-height: 24px;
  }
</style>
