    <template>
      <div>
        <ion-header>
          <ion-toolbar>
            <ion-title>{{ title }}</ion-title>
          </ion-toolbar>
        </ion-header>
        <ion-content class="ion-margin">
          <div>
          <h1>Hello</h1>
          <p>test</p>
          <p>test</p>
          </div>

        </ion-content>
      </div>
    </template>

    <script>
    import { IonContent, IonHeader, IonTitle, IonToolbar } from '@ionic/vue';
    import { defineComponent } from 'vue';

    export default defineComponent({
      name: 'Modal',
      props: {
        title: { type: String, default: 'Super Modal' },
      },
      components: { IonContent, IonHeader, IonTitle, IonToolbar }
    });
    </script>