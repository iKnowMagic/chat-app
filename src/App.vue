<template>
  <div class="main-container">
    <div class="promo-container">
      <div class="phone">
        <div class="phone-header">
          <div class="header-caret">
            <i class="icon-left-open" />
          </div>
          <div class="header-avatar">
            <img src="@/assets/images/avatar.jpg" />
          </div>
          <div class="header-text">
            <div class="header-text-title">
              Samuel Green
            </div>
            <div class="header-text-subtitle">
              Available to Walk
            </div>
          </div>
          <div class="header-menu">
            <i class="icon-dot-3" />
          </div>
        </div>
        <div class="phone-body">
          <div class="message-text-sent">
            That sounds great. I'd be happy to discuss more.
          </div>
          <div class="message-text-sent">
            Could you send over some pictures of your dog, please?
          </div>
          <div class="message-pictures">
            <img src="@/assets/images/dog-image-1.jpg" />
            <img src="@/assets/images/dog-image-2.jpg" />
            <img src="@/assets/images/dog-image-3.jpg" />
          </div>
          <div class="message-text-received">
            Here are a few pictures. She's a happy girl!
          </div>
          <div class="message-text-received">
            Can you make it?
          </div>
          <div class="message-text-sent">
            She looks so happy! The time we discussed works. How long shall I
            take her out for?
          </div>
          <div class="message-proposal">
            <div class="proposal-circle"></div>
            <div class="proposal-text">
              30 minute walk
            </div>
            <div class="proposal-price">
              $29
            </div>
          </div>
          <div class="message-proposal">
            <div class="proposal-circle"></div>
            <div class="proposal-text">
              1 hour walk
            </div>
            <div class="proposal-price">
              $49
            </div>
          </div>
        </div>
        <div class="phone-footer">
          <div class="send-message">
            <div class="send-message-placeholder">
              Type a message...
            </div>
            <div class="send-message-trigger">
              <i class="icon-right-open" />
            </div>
          </div>
        </div>
      </div>
      <div class="text-container">
        <div class="title">Simple booking</div>
        <div class="intro">
          Stay in touch with our dog walkers through the chat interface. This
          makes it easy to discuss arrangements and make bookings. Once the walk
          has been completed you can rate your walker and book again all through
          the chat.
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
